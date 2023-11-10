---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  HighCritical: true
  Lethal: true
Category: Special
Damage1: Special
Damage2: ''
Description: With a flicker of its claws, Palkia defragments the space around its
  foe. Those who survive rarely do peserve their original shape.
Effect: Lethal. High Critical.
Name: Spacial Rend
Power: 4
Target: Foe
Type: Dragon
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