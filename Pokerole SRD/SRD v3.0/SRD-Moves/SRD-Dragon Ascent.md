---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: -1
    Stats:
    - Def
    - SpDef
Attributes:
  Lethal: true
  Unique: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user rises above the clouds and then comes crashing down against
  its foe in an instant. The strike is brutal for the both of them.
Effect: Single Target. Lethal. Unique. Reduce by 1 the User's Defense and Sp. Defense.
Name: Dragon Ascent
Power: 5
Target: Foe
Type: Flying
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