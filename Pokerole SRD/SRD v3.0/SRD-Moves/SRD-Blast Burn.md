---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  AccuracyReduction: -1
  Lethal: true
  MustRecharge: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon creates an enormous blast of infernal flames, surviving\
  \ would be a miracle!"
Effect: Single Target. Low Accuracy 1. Lethal. Must Recharge.
Name: Blast Burn
Power: 6
Target: Foe
Type: Fire
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