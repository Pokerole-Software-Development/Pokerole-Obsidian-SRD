---
Accuracy1: Dexterity
Accuracy2: Channel/Nature
AddedEffects: {}
Attributes:
  PhysicalRanged: true
  ProjectileMove: true
  Ranged: true
  SuccessiveActions: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon starts shooting seed as if they were a machine gun."
Effect: Single Target. Ranged. Successive Actions. Projectile Moves.
Name: Bullet Seed
Power: 1
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