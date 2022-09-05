---
Accuracy1: Dexterity
Accuracy2: Nature
Damage1: Special
Damage2: ''
Description: The user creates a ball of energy that will use the climate around it
  to grow in size and power.
DmgType: Special
Effect: 'If the battlefield is under a Weather, add +2 to the Damage Roll and change
  the Type of the Move accordingly: Sun-Fire. Rain-Water. Hail-Ice. Sandstorm-Rock.
  Wind-Flying.'
Name: Weather Ball
Power: 2
Target: Foe
Type: Normal
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