---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 1
    Type: Poison
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: "A wave of black water spouts all around the user. It\u2019s knee-high\
  \ and rising. Fighting in such unsanitary conditions is not a good idea."
Effect: Area Move. Roll 1 Chance Die to Poison those affected.
Name: Sludge Wave
Power: 3
Target: Area
Type: Poison
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