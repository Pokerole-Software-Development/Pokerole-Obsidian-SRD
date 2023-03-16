```dataview
TABLE WITHOUT ID
Number, file.link AS Link, embed(link(HomeSprite)) AS Image
FROM #PokeroleSRD/Pokedex 
WHERE good-starter = "Yes"
SORT Number ASC
```