---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Targets
    ChanceDice: 1
    Stages: -1
    Stats:
    - Dexterity
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: "Dozens of bubbles are sent floating through the battlefield. The foes\
  \ can\u2019t resist the temptation to burst the pretty bubbles, only for the bubbles\
  \ to explode for real when they do."
Effect: Target All Foes in Range. Roll 1 Chance Die to Reduce by 1 the Dexterity of
  those affected.
Name: Bubble
Power: 2
Target: All Foes
Type: Water
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