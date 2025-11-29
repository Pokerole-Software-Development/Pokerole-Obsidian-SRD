---
Accuracy1: Beauty
Accuracy2: Charm
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -2
    Stats:
    - Special
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon shows off their attractiveness and even flirts with the\
  \ opponents, those who fall for their charms can\u2019t keep focus on the battle."
Effect: Target All Foes in Range. Reduce by 2 the Special of those affected.
Name: Captivate
Power: 0
Target: All Foes
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