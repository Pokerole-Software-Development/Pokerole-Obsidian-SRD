---
Accuracy1: Strength
Accuracy2: Athletic
AddedEffects: {}
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon shoots a projectile. Correction: the Pok\xE9mon IS the\
  \ projectile."
Effect: Single Target. Projectile Move. *Add 1 Extra Die to the Damage Pool of this
  Move for every point on Dexterity the Target has that surpasses the User's. Up to
  5 Dice may be added this way.
Name: Gyro Ball
Power: 1
Target: Foe
Type: Steel
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