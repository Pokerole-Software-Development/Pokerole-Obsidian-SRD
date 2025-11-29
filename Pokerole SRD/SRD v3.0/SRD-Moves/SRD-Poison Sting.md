---
Accuracy1: Strength
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Poison
Attributes:
  PhysicalRanged: true
  Ranged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: A tiny stab that causes big troubles.
Effect: Single Target. Ranged. Roll 3 Chance Dice to Poison the Target.
Name: Poison Sting
Power: 1
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