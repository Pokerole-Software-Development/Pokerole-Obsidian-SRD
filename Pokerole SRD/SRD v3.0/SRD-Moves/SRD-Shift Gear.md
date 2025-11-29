---
Accuracy1: Dexterity
Accuracy2: Athletic
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: 1
    Stats:
    - Strength
  - Affects: Targets
    Stages: 2
    Stats:
    - Dexterity
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "Once the Pok\xE9mon shifts to the fifth gear, nothing will stop them."
Effect: Target Self. Increase the User's Strength by 1 and its Dexterity by 2.
Name: Shift Gear
Power: 0
Target: Self
Type: Steel
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