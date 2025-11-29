---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects: {}
Attributes:
  AccuracyReduction: -1
  AlwaysCrit: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The user locates the most exposed parts of its foe and sends a gelid\
  \ breath against it. The sudden chill goes right through the foe\u2019s spine."
Effect: Single Target. Low Accuracy 1. This Move is always considered to be a Critical
  hit and gets the proper Bonus for it.
Name: Frost Breath
Power: 2
Target: Foe
Type: Ice
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