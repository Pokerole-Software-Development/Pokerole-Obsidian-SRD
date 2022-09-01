Change the type listed after the semicolons to change which type appears in the table. 

**Type**:: Fairy

```dataview
TABLE
Name
FROM #PokeroleSRD/Pokedex 
WHERE 
Type1 = this.Type OR Type2 = this.Type
```
