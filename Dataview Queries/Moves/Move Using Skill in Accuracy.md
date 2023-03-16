Change the value after the semi colons to change the table. 

**Skill**:: Will

```dataview
TABLE
Name
FROM #PokeroleSRD/Moves 
WHERE 
lower(Accuracy1) = lower(this.Skill) OR lower(Accuracy2) = lower(this.Skill)
```
