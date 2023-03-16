---
Accuracy1: Vitality
Accuracy2: Nature
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon swallows the energy she was storing to restore some damage,
  it recovers its normal size afterwards.
Effect: Must have used the move "Stockpile" prior to this Move, otherwise it will
  fail. If successful spend 1 Will point to activate. User restores 2 Health points.
  Loses the effects of stockpile. The Pokemon must rest an hour before using Swallow
  again.
Name: Swallow
Power: 0
Target: User
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