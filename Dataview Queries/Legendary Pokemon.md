```dataview
TABLE WITHOUT ID
Number, Name, file.link AS Link
FROM #PokeroleSRD/Pokedex 
WHERE Legendary = "Yes"
SORT Number ASC
```