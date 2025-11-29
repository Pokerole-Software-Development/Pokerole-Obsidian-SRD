---
Accuracy1: Strength
Accuracy2: Channel
AddedEffects: {}
Attributes:
  AccuracyReduction: -2
  Lethal: true
  PhysicalRanged: true
  Ranged: true
  Unique: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: Giant blades emerge from the earth impaling the unlucky souls nearby.
  Do you think you are safe in the air? Think again...
Effect: Target All Foes in Range. Low Accuracy 2. Ranged. Lethal. Unique. Ignore the
  Target's Immunity to Ground-Type Damage. If a Target is "Out of Range" due to using
  any Move, this Move hits anyways.
Name: Precipice Blades
Power: 5
Target: All Foes
Type: Ground
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