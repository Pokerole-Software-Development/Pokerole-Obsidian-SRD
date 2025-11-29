---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Block
Attributes:
  AccuracyReduction: -2
  BlockDamagePool: 2
  Duration: 4
  OngoingDamage: true
Category: Special
Damage1: Special
Damage2: ''
Description: The user creates a vortex of fire that remains spinning in the battlefield,
  trapping the foe within.
Effect: Single Target. Low Accuracy 2. Blocks. Ongoing Damage. Duration 4 Rounds.
  Increase the Target's difficulty to Evade at Storyteller's discretion.
Name: Fire Spin
Power: 2
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