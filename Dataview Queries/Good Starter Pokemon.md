```dataview
TABLE WITHOUT ID
Number, Name, file.link AS Link
FROM #PokeroleSRD/Pokedex 
WHERE good-starter = "Yes"
SORT Number ASC
```