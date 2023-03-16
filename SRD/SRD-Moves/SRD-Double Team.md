---
Accuracy1: Dexterity
Accuracy2: Evasion
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: SpedUp
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user moves rapidly around the foe, creating illusory copies of itself.
Effect: The User can now make up to 5 Evasions per Round.
Name: Double Team
Power: 0
Target: User
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