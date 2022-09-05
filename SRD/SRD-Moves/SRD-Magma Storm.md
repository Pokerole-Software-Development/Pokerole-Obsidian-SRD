---
Accuracy1: Special
Accuracy2: Channel
Damage1: Special
Damage2: ''
Description: The Pokemon shoots a fiery eruption to its foe. Unable to escape and
  surrounded by the unbearable heat the foe's survival is at risk.
DmgType: Special
Effect: Blocks. Roll 3 Damage Dice at the end of each Round. Lasts 4 Rounds. -2 Accuracy.
Name: Magma Storm
Power: 4
Target: Foe
Type: Fire
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