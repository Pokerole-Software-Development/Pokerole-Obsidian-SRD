---
Accuracy1: Strength
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Lethal: true
  PhysicalRanged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: Out of nowhere, pointy shards come raining from the sky towards the foes,
  even flying creatures will fall to the ground if they are knocked by them. Take
  cover, this is gonna hurt.
Effect: Lethal. Ranged. All Foes in Range. If successful, Flying and Levitating Pokemon
  can be hit by Ground-Type Moves for the rest of the scene.
Name: Thousand Arrows
Power: 3
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