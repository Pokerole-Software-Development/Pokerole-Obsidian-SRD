```dataview
TABLE WITHOUT ID
Number, Name, file.link AS Link
FROM #PokeroleSRD/Pokedex 
WHERE GoodStarter = "Yes"
SORT Number ASC
```