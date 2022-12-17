---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: User
    ChanceDice: 1
    Stages: 1
    Stats:
    - Strength
    - Dexterity
    - Special
    - Def
    - SpDef
Attributes: {}
Damage1: Special
Damage2: ''
Description: The Pokemon sends out a goosebump-inducing, repulsive wind that might
  make the user feel an evil rush.
DmgType: Special
Effect: Roll 1 Chance Dice to Increase the User's Strength, Dexterity, Special, Defense,
  and Sp. Defense.
Name: Ominous Wind
Power: 2
Target: Foe
Type: Ghost
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