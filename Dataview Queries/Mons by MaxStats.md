**Legendaries**:: No
**Megas**:: false
*"true" or "false"*
**Limit**:: 50

```dataview
TABLE
Type, row.MaxStrength+row.MaxDexterity+row.MaxVitality+row.MaxSpecial+row.MaxInsight AS MaxStat,
embed(link(HomeSprite)) AS Sprite
FROM #PokeroleSRD/Pokedex 
Where Legendary = this.Legendaries
Where contains(row.Name, "Mega-") = this.Megas
SORT
row.MaxStrength+row.MaxDexterity+row.MaxVitality+row.MaxSpecial+row.MaxInsight DESC
LIMIT this.Limit
```