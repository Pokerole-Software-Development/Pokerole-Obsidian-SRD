---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Priority: 1
  SuccessiveActions: true
Damage1: Special
Damage2: ''
Description: The Pokemon quickly throws sharp jets of water in the shape of a shuriken.
DmgType: Special
Effect: Ranged. Priority 1. Successive Actions.
Name: Water Shuriken
Power: 1
Target: Foe
Type: Water
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