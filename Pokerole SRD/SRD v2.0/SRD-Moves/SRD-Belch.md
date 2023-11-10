---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  AccuracyReduction: 1
Category: Special
Damage1: Special
Damage2: ''
Description: The user lets out a horrible belch on the target. The air contains toxins
  that deal a terrible damage.
Effect: The user must eat something before using this Move. -1 Accuracy.
Name: Belch
Power: 5
Target: Foe
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