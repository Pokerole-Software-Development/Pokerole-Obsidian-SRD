---
Accuracy1: Insight
Accuracy2: Intimidate
AddedEffects: {}
Attributes:
  FistMove: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon focuses all of their rage into a single fist, the more\
  \ they suffered the more dark energy will concentrate."
Effect: Single Target. Fist Move. *Add 2 Extra Dice to the Damage pool of this Move
  for every time the User has received Damage this Round, up to 8 Dice may be added
  this way.
Name: Rage Fist
Power: 2
Target: Foe
Type: Ghost
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