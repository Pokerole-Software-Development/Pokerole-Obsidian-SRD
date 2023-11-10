---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 2
    Type: Paralyze
Attributes:
  AccuracyReduction: 2
Category: Physical
Damage1: Strength
Damage2: ''
Description: Zekrom delivers a powerful tackle while discharging lightning through
  its body. The foe is rendered unable to move, either by the strike or the electricity
Effect: Roll 2 Chance Dice to Paralyze the foe. -2 Accuracy.
Name: Bolt Strike
Power: 6
Target: Foe
Type: Electric
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