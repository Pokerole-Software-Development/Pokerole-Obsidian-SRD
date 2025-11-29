---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Block
Attributes:
  AccuracyReduction: -1
  BlockDamagePool: 2
  Duration: 4
  OngoingDamage: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon uses all their strength to restrain to the foe and keep\
  \ them in place."
Effect: Single Target. Low Accuracy 1. Blocks. Ongoing Damage. Duration 4 Rounds.
  Increase the Target's difficultty to Evade at Storyteller's discretion.
Name: Bind
Power: 1
Target: Foe
Type: Normal
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