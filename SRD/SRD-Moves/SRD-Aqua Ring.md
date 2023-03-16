---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  Ailments:
  - Affects: Target
    Rounds: 4
    Type: AquaRingLifeDew
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user coats itself in a ring of special flowing water that lessens
  the pain.
Effect: If successful spent 1 Will point to activate. At the end of each Round, recover
  1 HP. Lasts 4 Rounds.
Name: Aqua Ring
Power: 0
Target: User
Type: Water
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