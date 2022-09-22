---
DexID: 0793
Moves:
- - Master
  - '[[SRD-Fell Stinger|Fell Stinger]]'
- - Master
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Master
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Master
  - '[[SRD-Power-Up Punch|Power-Up Punch]]'
- - Master
  - '[[SRD-Reversal|Reversal]]'
- - Master
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Master
  - '[[SRD-Comet Punch|Comet Punch]]'
- - Master
  - '[[SRD-Harden|Harden]]'
- - Master
  - '[[SRD-Bulk Up|Bulk Up]]'
- - Master
  - '[[SRD-Vital Throw|Vital Throw]]'
- - Master
  - '[[SRD-Endure|Endure]]'
- - Master
  - '[[SRD-Leech Life|Leech Life]]'
- - Master
  - '[[SRD-Taunt|Taunt]]'
- - Master
  - '[[SRD-Mega Punch|Mega Punch]]'
- - Master
  - '[[SRD-Counter|Counter]]'
- - Master
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Master
  - '[[SRD-Lunge|Lunge]]'
- - Master
  - '[[SRD-Dynamic Punch|Dynamic Punch]]'
- - Master
  - '[[SRD-Superpower|Superpower]]'
- - Master
  - '[[SRD-Focus Punch|Focus Punch]]'
- - Master
  - '[[SRD-Drain Punch|Drain Punch]]'
- - Master
  - '[[SRD-Outrage|Outrage]]'
- - Master
  - '[[SRD-Stomping Tantrum|Stomping Tantrum]]'
Name: Buzzwole
Species: '[[SRD-Buzzwole|Buzzwole]]'
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
