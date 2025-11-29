---
Accuracy1: ''
Accuracy2: ''
AddedEffects: {}
Attributes:
  Reaction: 1
Category: Support
Damage1: ''
Damage2: ''
Description: "Not being the best suited for a task doesn\u2019t mean you won\u2019\
  t do your part in helping out. The best teams work together!"
Effect: Target One Ally. Reaction 1. Roll your Accuracy as if it were Chance dice.
  Add 1 die to the Accuracy Roll of your Ally for each Success (result of 6) obtained
  this way. Up to 3 Characters may attempt to help a single Action. Up to 6 Dice may
  be added this way.
Name: Help Another
Power: 0
Target: One Ally
Type: Typeless
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