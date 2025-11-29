---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  Charge: true
  FistMove: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The user must focus on delivering the greatest punch in history, if\
  \ they succeed they\u2019ll be known as the One-Punch Pok\xE9mon."
Effect: Single Target. Fist Move. Charge Move. The User Flinches if it is hit while
  Charging this Move.
Name: Focus Punch
Power: 6
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