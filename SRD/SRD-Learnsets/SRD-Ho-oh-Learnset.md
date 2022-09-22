---
DexID: '0250'
Moves:
- - Master
  - '[[SRD-Gust|Gust]]'
- - Master
  - '[[SRD-Brave Bird|Brave Bird]]'
- - Master
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Master
  - '[[SRD-Sunny Day|Sunny Day]]'
- - Master
  - '[[SRD-Fire Blast|Fire Blast]]'
- - Master
  - '[[SRD-Sacred Fire|Sacred Fire]]'
- - Master
  - '[[SRD-Punishment|Punishment]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Safeguard|Safeguard]]'
- - Master
  - '[[SRD-Recover|Recover]]'
- - Master
  - '[[SRD-Future Sight|Future Sight]]'
- - Master
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Master
  - '[[SRD-Calm Mind|Calm Mind]]'
- - Master
  - '[[SRD-Sky Attack|Sky Attack]]'
- - Master
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Master
  - '[[SRD-Weather Ball|Weather Ball]]'
- - Master
  - '[[SRD-Solar Beam|Solar Beam]]'
- - Master
  - '[[SRD-Flash|Flash]]'
- - Master
  - '[[SRD-Hidden Power|Hidden Power]]'
- - Master
  - '[[SRD-Defog|Defog]]'
- - Master
  - '[[SRD-Strength|Strength]]'
- - Master
  - '[[SRD-Fly|Fly]]'
Name: Ho-oh
Species: '[[SRD-Ho-oh|Ho-oh]]'
---

#PokeroleSRD/Learnsets

## `= this.Name` Learnset

**DexID:** `= this.DexID`

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1] AS Move
FROM #PokeroleSRD/Learnsets
flatten moves as T
where file.path = this.file.path
```
