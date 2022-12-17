---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Flinch
Attributes:
  AccuracyReduction: 1
  Charge: true
  HighCritical: true
  Lethal: true
Damage1: Strength
Damage2: ''
Description: The Pokemon darts from the sky with a graceful and lethal strike, propelling
  with the wind, crushing the foe to the ground.
DmgType: Physical
Effect: Lethal. High Critical. Charge Move. Roll 3 Chance Dice to Flinch the foe.
  -1 Accuracy.
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

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`