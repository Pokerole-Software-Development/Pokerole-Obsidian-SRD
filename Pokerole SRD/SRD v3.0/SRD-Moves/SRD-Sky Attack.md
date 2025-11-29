---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Flinch
Attributes:
  AccuracyReduction: -1
  Charge: true
  HighCritical: true
  Lethal: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "In a graceful but lethal strike, the Pok\xE9mon takes a deep dive towards\
  \ the foe as if the sky was falling down right on top of it"
Effect: Single Target. Low Accuracy 1. Charge Move. High Critical. Lethal. Roll 3
  Chance Dice to Flinch the Target.
Name: Sky Attack
Power: 6
Target: Foe
Type: Flying
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