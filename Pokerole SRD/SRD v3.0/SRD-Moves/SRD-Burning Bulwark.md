---
Accuracy1: Special
Accuracy2: Nature
AddedEffects: {}
Attributes:
  Ranged: true
  Reaction: '4'
  ShieldMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon lights a fire coat around itself as a protective barrier.\
  \ It is not a good idea to touch it."
Effect: Target Self. Reaction 4. Shield Move. Reduce 3 Damage the User would receive
  from a Damaging Move. *If the Foe used a Non-Ranged Physical Move, inflicct 1st
  Degree Burn to it.
Name: Burning Bulwark
Power: 0
Target: Self
Type: Fire
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