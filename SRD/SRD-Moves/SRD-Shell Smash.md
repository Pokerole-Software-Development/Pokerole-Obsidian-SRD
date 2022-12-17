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
Damage1: ''
Damage2: ''
Description: By breaking its own shell, the user sacrifices defense in exchange of
  being free to fight with all its power.
DmgType: Support
Effect: Increase the User's Strength, Special, Dexterity by 2. Reduce the User's Defense
  and Special Defense by 2.
Name: Shell Smash
Power: 0
Target: User
Type: Normal
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`