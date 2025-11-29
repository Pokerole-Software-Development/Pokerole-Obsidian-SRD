---
Accuracy1: Strength
Accuracy2: Channel/Athletic
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 1
    Type: Burn2
Attributes:
  AccuracyReduction: -1
  PhysicalRanged: true
  ProjectileMove: true
  Ranged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon lights a heavy stone on fire and kicks it while it\u2019\
  s ablaze. The hit is pretty heavy already, the fire is just for showing off."
Effect: Single Target. Low Accuracy 1. Projectile Move. Ranged. Roll 1 Chance die
  to inflict 2nd Degree Burn on the Target.
Name: Pyro Ball
Power: 5
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