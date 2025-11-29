---
Accuracy1: Strength
Accuracy2: Brawl/Athletic
AddedEffects:
  StatChanges:
  - Affects: Targets
    ChanceDice: 5
    Stages: -1
    Stats:
    - Def
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: A hit powerful enough to destroy rocks and crack armor.
Effect: Single Target. Roll 5 Chance Dice to Reduce the Target's Defense by 1.
Name: Rock Smash
Power: 2
Target: Foe
Type: Fighting
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