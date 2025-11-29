---
Accuracy1: Special
Accuracy2: Perform
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: LuckyChant
Attributes:
  Duration: wholeScene
  Unique: true
Category: Support
Damage1: ''
Damage2: ''
Description: The magical incantation of an old priestess, through dance and song,
  good fortune and divine protection will come to you. This Move also removes evil
  spirits and curses.
Effect: Target User and Allies in Range. Unique. Targets can Re-roll one un-successful
  die from all their rolls. Critical Hits do not grant Bonus dice against the Targets.
  Whole Scene Duration. Out of battle, good things happen at Storyteller's Discretion.
Name: Lucky Chant
Power: 0
Target: All Allies
Type: Normal
---

#PokeroleSRD/Moves

### `= this.name`
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Category          | Power          |
| ------------- | --------------- | ----------------  | -------------- |
| `= this.Type` | `= this.Target` | `= this.Category` | `= this.Power` | 

**Effect:** `= this.Effect`