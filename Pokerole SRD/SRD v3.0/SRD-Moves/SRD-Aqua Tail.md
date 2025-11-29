---
Accuracy1: Dexterity/Strength
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Flinch
Attributes:
  AccuracyReduction: -1
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user sways their tail to create a pocket whirlpool in which the foe
  gets sucked in by the spinning motion.
Effect: Single Target. Low Accuracy 1. Roll 3 Chance Dice to Flinch the Target.
Name: Aqua Tail
Power: 3
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