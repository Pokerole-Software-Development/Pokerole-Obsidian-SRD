---
Accuracy1: Dexterity
Accuracy2: Intimidate
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -2
    Stats:
    - Def
Attributes:
  Reaction: '4'
  ShieldMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: In a reckless action, the user charges against the foe to stop its momentum
  and block its incoming attack. Being so close allows the user to reach for weak
  spots.
Effect: Target Self. Reaction 4. Shield Move. Reduce 3 Damage the User would receive
  from a Damaging Move. *If the Foe used a Non-Ranged Physical Move against the user
  Reduce the foe's Defense by 2.
Name: Obstruct
Power: 0
Target: Self
Type: Dark
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