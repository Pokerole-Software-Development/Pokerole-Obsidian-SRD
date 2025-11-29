---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  PhysicalRanged: true
  Ranged: true
  WindMove: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: A raging blizzard of petals and leaves sweeps through the entire area,
  leaving a pleasant floral scent and destruction in its wake.
Effect: Area Move. Ranged. Wind Move.
Name: Petal Blizzard
Power: 3
Target: Area
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