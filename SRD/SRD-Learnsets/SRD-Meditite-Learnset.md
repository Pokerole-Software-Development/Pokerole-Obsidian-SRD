---
DexID: '0307'
Moves:
- - Starter
  - '[[SRD-Bide|Bide]]'
- - Starter
  - '[[SRD-Detect|Detect]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - Beginner
  - '[[SRD-Meditate|Meditate]]'
- - Beginner
  - '[[SRD-Endure|Endure]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Hidden Power|Hidden Power]]'
- - Amateur
  - '[[SRD-Mind Reader|Mind Reader]]'
- - Amateur
  - '[[SRD-Feint|Feint]]'
- - Amateur
  - '[[SRD-Calm Mind|Calm Mind]]'
- - Amateur
  - '[[SRD-Force Palm|Force Palm]]'
- - Amateur
  - '[[SRD-High Jump Kick|High Jump Kick]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Psych Up|Psych Up]]'
- - Ace
  - '[[SRD-Acupressure|Acupressure]]'
- - Ace
  - '[[SRD-Power Trick|Power Trick]]'
- - Ace
  - '[[SRD-Reversal|Reversal]]'
- - Ace
  - '[[SRD-Recover|Recover]]'
- - Ace
  - '[[SRD-Counter|Counter]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Foresight|Foresight]]'
- - Pro
  - '[[SRD-Guard Swap|Guard Swap]]'
- - Pro
  - '[[SRD-Power Swap|Power Swap]]'
Name: Meditite
Species: '[[SRD-Meditite|Meditite]]'
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
