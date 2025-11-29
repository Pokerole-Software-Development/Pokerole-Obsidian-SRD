---
Accuracy1: Tough
Accuracy2: Intimidate
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -1
    Stats:
    - Strength
    - Special
Attributes:
  SwitcherMove: User
Category: Support
Damage1: ''
Damage2: ''
Description: The user throws one last threat against the foe before taking their leave.
  The foe is left too frightened to try to stand up against the user and their gang.
Effect: Single Target. Switcher Move for the User. Reduce by 1 the Foe's Strength
  and Special.
Name: Parting Shot
Power: 0
Target: Foe
Type: Dark
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