Change the type listed after the semicolons to change which type appears in the table. 

**Type**:: Water

```dataview
TABLE
Type, embed(link(HomeSprite)) AS Sprite
FROM #PokeroleSRD/Pokedex 
WHERE 
Type1 = this.Type OR Type2 = this.Type
SORT number ASC
```
