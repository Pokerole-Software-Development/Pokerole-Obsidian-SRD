---
Accuracy1: STRENGTH
Accuracy2: BRAWL
Damage1: STRENGTH
Damage2: ''
Description: The Pokemon focuses the sunlight on its sharp leaves, then releases the
  energy with a shattering block.
DmgType: PHYSICAL
Effect: Charge Move. If there is a Sunny Weather, you skip this Move's Charge action.
  If performed under Rain, Sandstorm, or Hail Weather, this Move takes two actions
  to Charge.
Name: Solar Blade
Power: 5
Target: Foe
Type: Grass
---

#PokeroleSRD/Moves

## `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`