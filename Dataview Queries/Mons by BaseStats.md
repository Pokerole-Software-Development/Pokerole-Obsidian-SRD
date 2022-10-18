**Legendaries**:: No
**Megas**:: false
*"true" or "false"*
**Limit**:: 50

```dataview
TABLE
Type, 
row.Strength+row.Dexterity+row.Vitality+row.Special+row.Insight AS BaseStat, 
embed(link(HomeSprite)) AS Sprite
FROM #PokeroleSRD/Pokedex 
Where Legendary = this.Legendaries
Where contains(row.Name, "Mega-") = this.Megas
SORT row.Strength+row.Dexterity+row.Vitality+row.Special+row.Insight DESC
LIMIT this.Limit
```