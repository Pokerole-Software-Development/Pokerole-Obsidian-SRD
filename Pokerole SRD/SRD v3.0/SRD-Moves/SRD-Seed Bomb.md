---
Accuracy1: Dexterity
Accuracy2: Channel/Nature
AddedEffects: {}
Attributes:
  PhysicalRanged: true
  ProjectileMove: true
  Ranged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: A giant seed is hurled against the target, the hit is not what knocks
  them down, the tree that explodes suddenly out of the seed is what does.
Effect: Single Target. Ranged. Projectile Move.
Name: Seed Bomb
Power: 3
Target: Foe
Type: Grass
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