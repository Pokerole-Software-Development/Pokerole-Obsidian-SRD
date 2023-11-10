---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  AccuracyReduction: 1
  Lethal: true
  Recoil: true
Category: Special
Damage1: Special
Damage2: ''
Description: By drawing energy from the Eternal Flower, the Pokemon unleashes all
  of its hurt. A beautiful light surrounds the area, yet the pain inside of its heart
  remains.
Effect: Lethal. Recoil. -1 Accuracy.
Name: Light Of Ruin
Power: 6
Target: Foe
Type: Fairy
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