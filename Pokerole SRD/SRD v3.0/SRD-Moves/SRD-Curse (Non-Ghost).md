---
Accuracy1: Vitality
Accuracy2: Clash
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: ''
Effect: Target Self. Increase by 1 the User's Strength and Defense. Reduce by 1 the
  User's Dexterity. This effect only works if the User is not Ghost-Type.
Name: Curse (Non-Ghost)
Power: 0
Target: Self
Type: Ghost
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