---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  DestroyShield: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The Pokemon uses its palm or claws to perform a one-armed chop that shatters
  even invisible barriers.
Effect: If a Barrier is in place on the foe's side (ie. Light Screen, Reflect) destroy
  the barrier and add 2 Extra Dice to the Damage Pool.
Name: Brick Break
Power: 3
Target: Foe
Type: Fighting
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