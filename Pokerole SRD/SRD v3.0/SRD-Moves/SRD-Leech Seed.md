---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Leech Seed
Attributes:
  AccuracyReduction: -1
Category: Support
Damage1: ''
Damage2: ''
Description: The foe is infected with seed saplings taking root on their body. As
  the saplings grow, they'll absorb the vital energy of the foe and send it back to
  the user.
Effect: "Single Target. Low Accuracy 1. Spend 1 Will point to activate. At the end\
  \ of each Round, Roll 2 Dice of Typeless Damage against the target ignoring defenses.\
  \ The User heals 1 HP for every damage dealt this way. Grass-Type Pok\xE9mon are\
  \ immune to this Effect. Whole Scene Duration."
Name: Leech Seed
Power: 0
Target: Foe
Type: Grass
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