---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  Priority: 1
Category: Physical
Damage1: Strength
Damage2: ''
Description: An attack as fast as lightning.
Effect: Priority 1. Double the Pokemon's movement speed.
Name: Quick Attack
Power: 2
Target: Foe
Type: Normal
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