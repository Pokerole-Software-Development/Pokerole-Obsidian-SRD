---
Accuracy1: Strength
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: User
    ChanceDice: 5
    Stages: 2
    Stats:
    - Def
Attributes:
  PhysicalRanged: true
  Ranged: true
  Unique: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon summons a storm of diamonds over the field. These diamonds\
  \ also serve as barriers the user can take cover into."
Effect: All foes in range. Ranged. Roll 5 chance dice to increase the user's defense
  by 2.
Name: Diamond Storm
Power: 4
Target: All Foes
Type: Rock
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