---
Accuracy1: Strength/Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  AccuracyReduction: -2
  PhysicalRanged: true
  ProjectileMove: true
  Ranged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The target can\u2019t take a yolk. Let\u2019s make them laugh with an\
  \ egg-cellent pun to crack them up."
Effect: Single Target. Low Accuracy 2. Ranged. Projectile Move.
Name: Egg Bomb
Power: 4
Target: Foe
Type: Normal
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