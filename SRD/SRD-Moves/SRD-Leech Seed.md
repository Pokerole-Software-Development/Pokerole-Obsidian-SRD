---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Leech Seed
Attributes:
  AccuracyReduction: 1
Damage1: ''
Damage2: ''
Description: The user plants some seeds on the target, the seeds sprout and restore
  the user's health by absorbing the foe's vital energy.
DmgType: Support
Effect: If successful spend 1 Will point to activate. At the end of each Round, Roll
  1 Dice of Damage to the foe. User heals for 1 HP for every damage dealt this way.
  Grass Type Pokemon are immune to this Move. -1 Accuracy.
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

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`