---
Accuracy1: Clever
Accuracy2: Nature
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Paralyze
Attributes:
  AccuracyReduction: -2
  PowderMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: A cloud of paralyzing pollen that affects the nerves and cramps the muscles
  of those who inhale it.
Effect: Single Target. Low Accuracy 3. Powder Move. Paralyze the Target.
Name: Stun Spore
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