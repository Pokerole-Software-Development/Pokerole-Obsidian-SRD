---
Accuracy1: Strength
Accuracy2: Nature
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Block
Attributes:
  AccuracyReduction: -2
  BlockDamagePool: 2
  Duration: 4
  OngoingDamage: true
  PhysicalRanged: true
  Ranged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon creates a pit of shifting sand around the foe to bury\
  \ it alive. The poor victim struggles for air as the sand keeps sinking it lower\
  \ and lower."
Effect: Single Target. Low Accuracy 2. Ranged. Blocks. Ongoing Damage. Duration 4
  Rounds. Increase the Target's difficulty to Evade at Storyteller's discretion.
Name: Sand Tomb
Power: 2
Target: Foe
Type: Ground
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