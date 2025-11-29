---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  HurtPenalty: true
  Lethal: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon converts its life-energy into a life-ending beam. No\
  \ exaggeration."
Effect: Target All foes in Range. Lethal. *Reduce 1 Dice from the Damage Pool for
  every missing HP the User has. Up to 5 dice may be removed this way.
Name: Dragon Energy
Power: 6
Target: All Foes
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