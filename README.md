# Export

Les documents peuvent être exporté à l'aide de `pandoc` vers plein de format tel que les pdf ou le wikitext

PDF:
```
pandoc --latex-engine=xelatex --variable geometry:margin=2.5cm -o statuts.pdf statuts.md
```

Wiki Text:
```
pandoc -t mediawiki -o statuts.txt statuts.md
```
