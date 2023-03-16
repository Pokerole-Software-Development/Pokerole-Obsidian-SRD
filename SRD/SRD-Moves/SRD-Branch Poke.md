---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: The Pokemon rudely starts poking its foe with a stick.
Effect: '-'
Name: Branch Poke
Power: 2
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