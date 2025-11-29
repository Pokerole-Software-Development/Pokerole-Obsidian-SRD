---
Accuracy1: SameasBaseMove
Accuracy2: ''
AddedEffects: {}
Attributes:
  MaxMove: true
  Reaction: '5'
  ShieldMove: true
Category: ''
Damage1: SameasBasePower
Damage2: ''
Description: ''
Effect: Target Max Self. Shield Move. Reaction 5. Reduce 5 Damage this Max Pokemon
  would receive from a Physical or Special Move. Negate the Added Effects of Any Move
  that targets the Max User
Name: Max Guard
Power: 0
Target: ''
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