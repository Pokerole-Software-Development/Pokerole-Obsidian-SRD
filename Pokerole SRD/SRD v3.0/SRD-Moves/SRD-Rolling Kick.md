---
Accuracy1: Dexterity
Accuracy2: Athletic
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Flinch
Attributes:
  AccuracyReduction: -2
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon jumps in the air and spins with one leg extended to land\
  \ an impressive kick against their foe."
Effect: Single Target. Low Accuracy 2. Roll 3 Chance Dice to Flinch the Target.
Name: Rolling Kick
Power: 2
Target: Foe
Type: Fighting
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