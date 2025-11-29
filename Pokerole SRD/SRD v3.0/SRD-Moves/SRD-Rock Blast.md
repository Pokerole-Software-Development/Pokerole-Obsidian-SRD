---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  AccuracyReduction: -1
  PhysicalRanged: true
  ProjectileMove: true
  Ranged: true
  SuccessiveActions: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: A rock shrapnel, the user shoots tiny bullet-like pebbles.
Effect: Single Target. Low Accuracy 1. Ranged. Successive Actions. Projectile Move.
Name: Rock Blast
Power: 1
Target: Foe
Type: Rock
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