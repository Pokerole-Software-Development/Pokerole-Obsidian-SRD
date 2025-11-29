---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  CutterMove: true
  HighCritical: true
  WindMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: A sharp wide wave of wind is sent out , everyone can feel it slicing
  throught their midsection.
Effect: Target All Foes in Range. High Critical. Wind Move. Cutter Move.
Name: Air Cutter
Power: 2
Target: All Foes
Type: Flying
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