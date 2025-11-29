---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Burn3
Attributes:
  AccuracyReduction: -3
  Lethal: true
Category: Special
Damage1: Special
Damage2: ''
Description: The user sets their target on fire with unforgiving flames. Abandon all
  hope.
Effect: Single Target. Low Accuracy 3. Lethal. Inflict 3rd Degree Burn on the Target.
Name: Inferno
Power: 4
Target: Foe
Type: Fire
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