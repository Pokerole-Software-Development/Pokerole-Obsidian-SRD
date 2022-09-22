Change the type listed after the semicolons to change which type appears in the table. 

**Type**:: Volt Absorb

```dataview
TABLE
Type, Abilities, embed(link(HomeSprite)) AS Sprite
FROM #PokeroleSRD/Pokedex 
WHERE 
Ability1 = this.Type OR Ability2 = this.Type OR HiddenAbility = this.Type OR EventAbilities = this.Type
SORT number ASC
```
