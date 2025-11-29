---
Accuracy1: Will
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -1
    Stats:
    - Accuracy
Attributes:
  Unique: true
Category: Support
Damage1: ''
Damage2: ''
Description: Put your faith on the moon, pray during dark times and it shall bring
  light into your heart, guide the strayed, and cast away the creatures from the shadows.
Effect: '*Target User or Target one Ally. Unique. If successful, spend 1 Will point
  to activate. Complete Heal. Heal all status Ailments on the Target. Reduce 1 success
  to all Accuracy Rolls of one foe.'
Name: Lunar Blessing
Power: 0
Target: Ally
Type: Psychic
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