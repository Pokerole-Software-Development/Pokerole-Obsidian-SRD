---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  AccuracyReduction: -2
  CutterMove: true
  Duration: 4
  HighCritical: true
  OngoingDamage: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The user slashes the foe using a sharp but brittle shell. Tiny spikes\
  \ from the shell are left embeded into the foe\u2019s wounds causing more damage\
  \ as the foe moves."
Effect: Single Target. Low Accuracy 2. High Critical. Cutter Move. Ongoing Damage
  with Duration of 4 Rounds.
Name: Ceaseless Edge
Power: 2
Target: Foe
Type: Dark
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