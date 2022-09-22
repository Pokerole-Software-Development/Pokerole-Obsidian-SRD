### Shows which Pokémon learn a given move, grouped by rank

**Move**:: Fire Punch

```dataview
TABLE WITHOUT ID
    Learned,
    rows.Species AS Species,
    length(rows.Species) AS SpeciesCount 
FROM #PokeroleSRD/Learnsets
flatten moves as T
where contains(T[1].name, this.Move)
Group by T[0] As Learned
```
