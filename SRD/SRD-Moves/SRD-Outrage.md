---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  Rampage: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user awakens their primal instinct as a dragon and unleashes its
  uncontrollable fury, destroying everything in its path. After that, the Pokemon
  is left disoriented and confused.
Effect: Rampage.
Name: Outrage
Power: 5
Target: Random Foe
Type: Dragon
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