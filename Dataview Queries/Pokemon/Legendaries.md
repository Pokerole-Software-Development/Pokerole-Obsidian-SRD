```dataview
TABLE
Type, embed(link(HomeSprite)) AS Sprite
FROM #PokeroleSRD/Pokedex 
WHERE Legendary = "Yes"
SORT Number ASC
```