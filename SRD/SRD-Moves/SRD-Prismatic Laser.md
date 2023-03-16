---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Lethal: true
  MustRecharge: true
Category: Special
Damage1: Special
Damage2: ''
Description: Through a prism, the user shoots a concentrated laser beam that pierces
  everything that comes in contact with it. The effort leaves the user mentally exhausted.
Effect: Lethal. Must Recharge.
Name: Prismatic Laser
Power: 6
Target: Foe
Type: Psychic
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