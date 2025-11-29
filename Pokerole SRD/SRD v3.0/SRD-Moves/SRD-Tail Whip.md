---
Accuracy1: Cute
Accuracy2: Perform
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -1
    Stats:
    - Def
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon whips their tail in such an adorable way the foes let\
  \ their guard down."
Effect: Target All Foes in Range. Reduce by 1 the Defense of those affected.
Name: Tail Whip
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