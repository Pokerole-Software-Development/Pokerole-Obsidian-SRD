---
Accuracy1: DEXTERITY
Accuracy2: CHANNEL
Damage1: STRENGTH
Damage2: ''
Description: The user hurls a projectile, usually a heavy rock that sends the foe
  down to the ground, leaving it unable to take off the ground afterwards.
DmgType: PHYSICAL
Effect: Ranged. Remove the foe's Immunity to Ground-Type Attacks.
Name: Smack Down
Power: 2
Target: Foe
Type: Rock
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