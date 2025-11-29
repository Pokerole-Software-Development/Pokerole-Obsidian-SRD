---
Accuracy1: Insight
Accuracy2: Alert
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: ForesightOdorSleuth
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon uses its developed senses and mental ability to foresee the
  immediate future.
Effect: The Foe cannot evade moves performed by the user. User's Normal and Fighting
  Moves can affect Ghost Types and Ghost Moves can affect Normal Types.
Name: Foresight
Power: 0
Target: Foe
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