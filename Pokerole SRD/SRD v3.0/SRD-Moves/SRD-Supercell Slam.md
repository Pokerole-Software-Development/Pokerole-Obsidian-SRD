---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  AccuracyReduction: -1
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user charges itself, jumps up high, then free-falls to crash on the
  target at a high speed. Beware of not ending up crashing directly against the floor.
Effect: Single Target. Low Accuracy 1. If the Accuracy roll fails, Roll 4 Dice of
  Typeless Damage against the user, ignoring defenses.
Name: Supercell Slam
Power: 4
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