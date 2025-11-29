---
Accuracy1: Strength
Accuracy2: Channel
AddedEffects: {}
Attributes:
  AccuracyReduction: -1
  Lethal: true
  MustRecharge: true
  PhysicalRanged: true
  ProjectileMove: true
  Ranged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "A giant boulder is blasted like a cannon ball towards the target. Leaving\
  \ a path of destruction and a subsequent explosion as the boulder crashes. Let the\
  \ pok\xE9mon catch their breath afterwards."
Effect: Single Target. Low Accuracy 1. Lethal. Ranged. Projectile Move. Must Recharge.
Name: Rock Wrecker
Power: 6
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