### This query finds all Pokemon that learn a move.

**Move**:: Rage Powder

```dataview
TABLE
    T[0] AS Learned,
    T[1].Name AS Move,
    embed(link(HomeSprite)) AS Sprite 
FROM #PokeroleSRD/Pokedex
flatten moves as T
where contains(T[1].name, this.Move)
Sort T[0]
```

---

### This query uses the list above, but also limits based on what rank the Pokemon learns that move. 

**Rank**:: Beginner

```dataview
TABLE
    T[0] AS Learned,
    T[1].Name AS Move,
    embed(link(HomeSprite)) AS Sprite 
FROM #PokeroleSRD/Pokedex
flatten moves as T
where contains(T[1].name, this.Move)
and contains(T[0], this.Rank)
```