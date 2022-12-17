---
Accuracy1: Will
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Curse
Attributes: {}
Damage1: ''
Damage2: ''
Description: The user mutters words that become an evil incantation, the curse may
  only be lifted by a medium or through divine intervention.
DmgType: Support
Effect: Roll half the user's HP as damage dice to itself, ignoring Defenses. The target
  will remove 1 success from all their rolls until the Curse is lifted.
Name: Curse
Power: 0
Target: Foe
Type: Ghost
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`