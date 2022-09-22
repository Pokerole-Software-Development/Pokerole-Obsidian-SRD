### This query finds all moves with a given name.

**Move**:: Foresight

```dataview
TABLE WITHOUT ID
    Species,
    T[0] AS Learned,
    T[1].Name AS Move,
    embed(link(Species.HomeSprite)) AS Sprite 
FROM #PokeroleSRD/Learnsets
flatten moves as T
where contains(T[1].name, this.Move)
Sort T[0]
```

---

### This query uses the moves specified above, but also limits based on what rank the Pokemon learns that move. 

**Rank**:: Beginner

```dataview
TABLE without id 
    Species,
    T[0] AS Learned,
    T[1].Name AS Move,
    embed(link(Species.HomeSprite)) AS Sprite 
FROM #PokeroleSRD/Learnsets
flatten moves as T
where contains(T[1].name, this.Move)
and contains(T[0], this.Rank)
```