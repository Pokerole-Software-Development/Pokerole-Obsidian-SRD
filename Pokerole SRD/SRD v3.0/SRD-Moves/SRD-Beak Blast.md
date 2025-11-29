---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: User
    Type: BeakBlast
Attributes:
  Charge: true
  PhysicalRanged: true
  ProjectileMove: true
  Ranged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon gets ready to release a boiling gas through its beak,\
  \ which gets incredibly hot. The resulting blast sounds like a train\u2019s horn."
Effect: Single Target. Charge Move. Ranged. Projectile Move. *If the User is hit by
  a Non-Ranged Physical Move while this Move is charging, inflict 2nd Degree Burn
  on the attacker.
Name: Beak Blast
Power: 4
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