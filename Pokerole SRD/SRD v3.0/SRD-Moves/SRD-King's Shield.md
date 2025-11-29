---
Accuracy1: Vitality
Accuracy2: Brawl
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -2
    Stats:
    - Strength
Attributes:
  Reaction: '4'
  ShieldMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: Off my chair, jester! The king sits there!
Effect: Target Self. Reaction 4. Shield Move. Reduce 3 Damage the User would receive
  from a Damaging Move. *If the Foe used a Non-Ranged Physical Move against the user,
  Reduce the foe's Strength by 2.
Name: King's Shield
Power: 0
Target: Self
Type: Steel
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