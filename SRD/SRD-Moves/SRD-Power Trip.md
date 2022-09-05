---
Accuracy1: Dexterity
Accuracy2: Brawl
Damage1: Strength
Damage2: ''
Description: In the heat of the battle, the Pokemon gets carried away, relishing in
  its own power.
DmgType: Physical
Effect: Add 1 Dice to the Damage Pool of this Move for every Attribute increase the
  user has. Up to 7 Dice may be added this way. (ie. the user has 2 increased points
  on Defense, add 2 Damage dice).
Name: Power Trip
Power: 1
Target: Foe
Type: Dark
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