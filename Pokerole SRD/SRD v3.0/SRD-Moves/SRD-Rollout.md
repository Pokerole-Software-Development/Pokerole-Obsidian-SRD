---
Accuracy1: Dexterity
Accuracy2: Athletic/Brawl
AddedEffects: {}
Attributes:
  AccuracyReduction: -1
  SuccessiveActions: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "When the foe sees this Pok\xE9mon rollin\u2019 they\u2019ll be hatin\u2019\
  ."
Effect: Single Target. Low Accuracy 1. Successive Actions. *If all 5 actions land
  successfully, add 1 Extra Die to the Damage Pool of the last hit of this Move. If
  the Pokemon used the Move "Defense Curl" in the same round, this Move's base Power
  becomes 2.
Name: Rollout
Power: 1
Target: Foe
Type: Rock
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