---
Accuracy1: Dexterity
Accuracy2: Stealth
AddedEffects: {}
Attributes: {}
Damage1: ''
Damage2: ''
Description: The Pokemon hides sharp and point rocks all over the foe's side of the
  battlefield.
DmgType: Support
Effect: Entry Hazard. Foe Pokemon that enter the battlefield lose 1 HP. This effect
  does not stack.
Name: Stealth Rock
Power: 0
Target: Battlefield
Type: Rock
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