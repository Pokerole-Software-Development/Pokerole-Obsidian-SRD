---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: -1
    Stats:
    - Dexterity
Attributes:
  AccuracyReduction: -1
  FistMove: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon uses its powerful gelid arms and strikes the foe with\
  \ a swing motion."
Effect: Single Target. Fist Move. Low Accuracy 1. Reduce User's Dexterity by 1.
Name: Ice Hammer
Power: 4
Target: Foe
Type: Ice
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