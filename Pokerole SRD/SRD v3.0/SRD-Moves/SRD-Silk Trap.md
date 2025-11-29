---
Accuracy1: Insight
Accuracy2: Stealth
AddedEffects: {}
Attributes:
  Ranged: true
  Reaction: '4'
  ShieldMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon weaves a thread of silk around specific parts of their\
  \ body, both as an armor and as a trap to snare their enemies."
Effect: Target Self. Reaction 4. Shield Move. Reduce 3 Damage the User would receive
  from a Damaging Move. *If the Foe used a Non-Ranged Physical Move, against the user
  Reduce the foe's Dexterity by 2.
Name: Silk Trap
Power: 0
Target: Self
Type: Bug
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