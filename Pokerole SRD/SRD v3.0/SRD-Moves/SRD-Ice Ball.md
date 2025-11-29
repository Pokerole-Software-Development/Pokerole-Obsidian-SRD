---
Accuracy1: Dexterity
Accuracy2: Athletic/Brawl
AddedEffects: {}
Attributes:
  AccuracyReduction: -1
  ProjectileMove: true
  SuccessiveActions: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon rolls into a snowball, getting bigger and bigger as they\
  \ keep rolling"
Effect: Single Target. Low Accuracy 1. Projectile Move. Successive Actions. *If all
  5 actions land successfully, add 1 Extra Die to the Damage Pool of the last hit
  of this Move. If the Pokemon used the Move "Defense Curl" in the same round, this
  Move's base Power becomes 2.
Name: Ice Ball
Power: 1
Target: Foe
Type: Ice
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