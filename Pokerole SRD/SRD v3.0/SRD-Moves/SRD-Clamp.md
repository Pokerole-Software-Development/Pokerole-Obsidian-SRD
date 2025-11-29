---
Accuracy1: Vitality
Accuracy2: Brawl/Stealth
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Block
Attributes:
  AccuracyReduction: -2
  BlockDamagePool: 2
  Duration: 4
  OngoingDamage: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "Lured by a beautiful pearl, the target is clamped by the user\u2019\
  s sturdy shell. The user will not release the target until they no longer feel movement."
Effect: Single Target. Low Accuracy 2. Block both User and Target. Ongoing Damage.
  Increase the Target's difficulty to Evade at Storyteller's discretion. Duration
  4 Rounds.
Name: Clamp
Power: 2
Target: Foe
Type: Water
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