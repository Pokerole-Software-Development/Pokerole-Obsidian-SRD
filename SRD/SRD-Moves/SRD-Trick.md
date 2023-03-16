---
Accuracy1: Special
Accuracy2: Allure
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: Control the target's mind to perform a simple non-hostile action, such
  as walking or handling an item.
Effect: The foe and the user swap Held Items.
Name: Trick
Power: 0
Target: Foe
Type: Psychic
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