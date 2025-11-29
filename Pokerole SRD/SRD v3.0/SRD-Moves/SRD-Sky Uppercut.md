---
Accuracy1: Dexterity
Accuracy2: Athletic
AddedEffects: {}
Attributes:
  AccuracyReduction: -1
  FistMove: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user attacks with an uppercut, throwing the foe skyward with lots
  of force. Even flyers are not safe from this attack.
Effect: Single Target. Fist Move. Low Accuracy 1. If the Target is Out of Range due
  to using "Fly", "Bounce" or "Sky Drop" this Move hits anyways.
Name: Sky Uppercut
Power: 3
Target: Foe
Type: Fighting
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