---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: BadlyPoison
Attributes:
  AccuracyReduction: -2
Category: Support
Damage1: ''
Damage2: ''
Description: This burning acid dissolves skin to enter the bloodstream directly. The
  poor victim feels like they are melting from the inside out. The clock is ticking.
Effect: Single Target. Low Accuracy 2. Badly Poison the Target.
Name: Toxic
Power: 0
Target: Foe
Type: Poison
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