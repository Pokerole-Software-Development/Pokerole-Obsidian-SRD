---
DexID: 0718
Moves:
- - Master
  - '[[SRD-Hurricane|Hurricane]]'
- - Master
  - '[[SRD-Razor Wind|Razor Wind]]'
- - Master
  - '[[SRD-Taunt|Taunt]]'
- - Master
  - '[[SRD-Roost|Roost]]'
- - Master
  - '[[SRD-Double Team|Double Team]]'
- - Master
  - '[[SRD-Air Slash|Air Slash]]'
- - Master
  - '[[SRD-Snarl|Snarl]]'
- - Master
  - '[[SRD-Oblivion Wing|Oblivion Wing]]'
- - Master
  - '[[SRD-Disable|Disable]]'
- - Master
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - Master
  - '[[SRD-Foul Play|Foul Play]]'
- - Master
  - '[[SRD-Phantom Force|Phantom Force]]'
- - Master
  - '[[SRD-Psychic|Psychic]]'
- - Master
  - '[[SRD-Dragon Rush|Dragon Rush]]'
- - Master
  - '[[SRD-Focus Blast|Focus Blast]]'
- - Master
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Master
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - Master
  - '[[SRD-Sky Attack|Sky Attack]]'
- - Master
  - '[[SRD-Tailwind|Tailwind]]'
- - Master
  - '[[SRD-Heat Wave|Heat Wave]]'
- - Master
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Master
  - '[[SRD-Defog|Defog]]'
Name: Yveltal
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
