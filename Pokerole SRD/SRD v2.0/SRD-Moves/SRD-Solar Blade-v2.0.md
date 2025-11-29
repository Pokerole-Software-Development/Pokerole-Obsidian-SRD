---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  Charge: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The Pokemon focuses the sunlight on its sharp leaves, then releases the
  energy with a shattering block.
Effect: Charge Move. If there is a Sunny Weather, you skip this Move's Charge action.
  If performed under Rain, Sandstorm, or Hail Weather, this Move takes two actions
  to Charge.
Name: Solar Blade
Power: 5
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