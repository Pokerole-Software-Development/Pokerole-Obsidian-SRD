---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  AccuracyReduction: -1
  Duration: 1
  Ranged: true
  SuccessiveActions: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon\u2019s scales burst out as if they were shrapnel from\
  \ a grenade."
Effect: Single Target. Low Accuracy 1. Ranged. Successive Actions. *If all 5 actions
  land successfully, Increase the User's Dexterity by 1, and lower the User's Defense
  by 1.
Name: Scale Shot
Power: 1
Target: Foe
Type: Dragon
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