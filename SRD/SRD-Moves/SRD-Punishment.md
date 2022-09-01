---
Accuracy1: DEXTERITY
Accuracy2: BRAWL
Damage1: STRENGTH
Damage2: ''
Description: The user takes advantage of its foe's strengths to use them against it.
DmgType: PHYSICAL
Effect: Add up to 7 Dice to the Damage Pool for every Increased Attribute the foe
  has. (ie. Foe has 1 Increased dice in Dexterity & Strength that equals +2 Dice on
  the Damage Pool of this attack).
Name: Punishment
Power: 1
Target: Foe
Type: Dark
---

#PokeroleSRD/Moves

## `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`