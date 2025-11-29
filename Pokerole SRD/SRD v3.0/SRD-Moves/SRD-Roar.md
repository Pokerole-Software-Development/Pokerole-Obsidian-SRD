---
Accuracy1: Strength
Accuracy2: Intimidate
AddedEffects: {}
Attributes:
  LateReaction: '6'
  SwitcherMove: Foe
  SwitcherMoveForFoe: true
Category: Support
Damage1: ''
Damage2: ''
Description: With a potent roar, to make the foe reconsider their intentions.
Effect: Single Target. Late Reaction 6. Switcher Move for the Foe. In the wild, the
  battle may end.
Name: Roar
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