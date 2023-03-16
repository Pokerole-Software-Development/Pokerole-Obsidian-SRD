### This query finds all Pokemon that learn a move.

```dataview
TABLE
    Type,
    Effect
FROM #PokeroleSRD/Moves
where contains(Effect, "Sound")
```

---