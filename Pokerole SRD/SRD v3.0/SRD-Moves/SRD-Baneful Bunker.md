---
Accuracy1: Vitality
Accuracy2: Nature
AddedEffects: {}
Attributes:
  Ranged: true
  Reaction: '4'
  ShieldMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: "The user encloses themselves inside a sturdy shell covered by poisonous\
  \ barbs, if a barb pinches the Target\u2019s skin, the wound will start to fester"
Effect: Target Self. Reaction 4. Shield Move. Reduce 3 Damage the User would receive
  from a Damaging Move. *If the Foe used a Non-Ranged Physical Move against the user,
  Poison the foe.
Name: Baneful Bunker
Power: 0
Target: Self
Type: Poison
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