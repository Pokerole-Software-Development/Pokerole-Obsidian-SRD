---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Block
Attributes:
  AccuracyReduction: -2
  BlockDamagePool: 3
  Duration: 4
  Lethal: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon shoots a fiery eruption to its foe. Unable to escape\
  \ and surrounded by the unbearable heat the foe\u2019s survival is at risk."
Effect: Single Target. Low Accuracy 2. Lethal. Blocks. Roll 3 Fire-Type Damage Dice
  ignoring defenses at the end of each Round. Duration 4 Rounds.
Name: Magma Storm
Power: 4
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