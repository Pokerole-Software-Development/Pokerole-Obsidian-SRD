```dataview
TABLE
Type, embed(link(HomeSprite)) AS Sprite
FROM #PokeroleSRD/Pokedex 
SORT number ASC
WHERE contains(Name, "Mega Form")
```