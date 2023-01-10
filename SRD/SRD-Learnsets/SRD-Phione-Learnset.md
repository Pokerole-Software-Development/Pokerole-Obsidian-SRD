---
Moves:
- - Master
  - '[[SRD-Bubble|Bubble]]'
- - Master
  - '[[SRD-Water Sport|Water Sport]]'
- - Master
  - '[[SRD-Charm|Charm]]'
- - Master
  - '[[SRD-Supersonic|Supersonic]]'
- - Master
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Master
  - '[[SRD-Acid Armor|Acid Armor]]'
- - Master
  - '[[SRD-Whirlpool|Whirlpool]]'
- - Master
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Master
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Master
  - '[[SRD-Dive|Dive]]'
- - Master
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Master
  - '[[SRD-Surf|Surf]]'
- - Master
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Master
  - '[[SRD-Heal Bell|Heal Bell]]'
- - Master
  - '[[SRD-Last Resort|Last Resort]]'
Name: Phione
Pokedex: '[[SRD-Phione|Phione]]'
---

#PokeroleSRD/Learnsets

## `= this.Name` Learnset

**Pokedex Entry:** `= this.Pokedex`

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1] AS Move
FROM #PokeroleSRD/Learnsets
flatten moves as T
where file.path = this.file.path
```
