---
Accuracy1: Special
Accuracy2: Nature
Damage1: ''
Damage2: ''
Description: The Pokemon digs around and moves the soil to make it ideal for plant
  growth.
DmgType: Support
Effect: Increase the Strength and Special of all Grass Type Pokemon in the battlefield.
Name: Rototiller
Power: 0
Target: Battlefield
Type: Ground
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