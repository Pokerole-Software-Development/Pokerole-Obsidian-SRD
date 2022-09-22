---
DexID: 0486
Moves:
- - Master
  - '[[SRD-Heavy Slam|Heavy Slam]]'
- - Master
  - '[[SRD-Crush Grip|Crush Grip]]'
- - Master
  - '[[SRD-Fire Punch|Fire Punch]]'
- - Master
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Master
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Master
  - '[[SRD-Dizzy Punch|Dizzy Punch]]'
- - Master
  - '[[SRD-Knock Off|Knock Off]]'
- - Master
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Master
  - '[[SRD-Foresight|Foresight]]'
- - Master
  - '[[SRD-Revenge|Revenge]]'
- - Master
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Master
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Master
  - '[[SRD-Payback|Payback]]'
- - Master
  - '[[SRD-Hidden Power|Hidden Power]]'
- - Master
  - '[[SRD-Psych Up|Psych Up]]'
- - Master
  - '[[SRD-Giga Impact|Giga Impact]]'
- - Master
  - '[[SRD-Substitute|Substitute]]'
- - Master
  - '[[SRD-Strength|Strength]]'
- - Master
  - '[[SRD-Superpower|Superpower]]'
- - Master
  - '[[SRD-Nature Power|Nature Power]]'
Name: Regigigas
Species: '[[SRD-Regigigas|Regigigas]]'
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
