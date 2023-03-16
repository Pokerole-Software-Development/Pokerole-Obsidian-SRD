### Shows which Pokémon learn a given move, grouped by rank

**Move**:: Foresight

```dataview
TABLE WITHOUT ID
    Learned,
    rows.Name AS Species,
    length(rows.Name) AS SpeciesCount 
FROM #PokeroleSRD/Pokedex
flatten moves as T
where contains(T[1].name, this.Move)
Group by T[0] As Learned
```
