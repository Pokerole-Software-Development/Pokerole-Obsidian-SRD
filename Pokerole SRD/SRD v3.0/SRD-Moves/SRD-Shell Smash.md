---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: 2
    Stats:
    - Strength
    - Special
    - Dexterity
  - Affects: User
    Stages: -2
    Stats:
    - Def
    - SpDef
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon breaks off their own shell. The foe mistakenly believed\
  \ the shell was for the Pok\xE9mon to protect themselves when it was actually there\
  \ to protect the foes from what\u2019s next."
Effect: Target Self. Increase by 2 the User's Strength, Special and Dexterity. Reduce
  by 2 the User's Defense and Sp. Defense.
Name: Shell Smash
Power: 0
Target: Self
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