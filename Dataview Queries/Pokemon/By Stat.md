**StatName**:: base-hp
**Legendaries**:: No
**Limit**:: 50

```dataview
TABLE
Type, row[this.StatName] AS Stat, embed(link(HomeSprite)) AS Sprite
FROM #PokeroleSRD/Pokedex 
Where Legendary = this.Legendaries
SORT row[this.StatName] DESC
LIMIT this.Limit
```