---
Accuracy1: Dexterity
Accuracy2: Channel
Damage1: Special
Damage2: ''
Description: The user snares the target's feet with grass, making it fall to the ground.
  The bigger the foe the harder the fall.
DmgType: Special
Effect: Add 1 Extra Dice to the Damage Pool for every 50 kgs. of weight on the foe,
  up to +4 Extra Dice.
Name: Grass Knot
Power: 1
Target: Foe
Type: Grass
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