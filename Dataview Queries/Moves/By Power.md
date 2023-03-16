```dataview
TABLE 
Power
FROM #PokeroleSRD/Moves 
sort Power ASC
where Damage1 != "Special" AND Damage1 != "Strength" AND DmgType != "Support"
```