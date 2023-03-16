**Legendaries**:: No
**Megas**:: false
*"true" or "false"*
**Limit**:: 50

```dataview
TABLE
Type, 
Strength+Dexterity+Vitality+Special+Insight AS BaseStat,
MaxStrength+MaxDexterity+MaxVitality+MaxSpecial+MaxInsight AS MaxStat,
embed(link(HomeSprite)) AS Sprite
FROM #PokeroleSRD/Pokedex 
WHERE Legendary = this.Legendaries
AND contains(Name, "(Mega Form") = this.Megas AND True
SORT Strength+Dexterity+Vitality+Special+Insight DESC
LIMIT this.Limit
```