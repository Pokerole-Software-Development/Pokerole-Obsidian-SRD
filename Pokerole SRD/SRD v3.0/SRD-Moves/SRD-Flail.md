---
Accuracy1: Vitality
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  HurtBonus: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user flails around trying to stay alive, as they get closer to fainting,
  more adrenaline will fuel their efforts of survival.
Effect: Single Target. *Add 1 Extra Die to the Damage Pool of this Move for every
  missing Point of HP the user has. Up to 5 Dice may be added this way.
Name: Flail
Power: 1
Target: Foe
Type: Normal
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