---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Rampage: true
Category: Special
Damage1: Special
Damage2: ''
Description: The Pokemon starts swirling petals around in a true display of nature's
  power, the petals are guided by the wind to strike the foe.
Effect: Rampage.
Name: Petal Dance
Power: 5
Target: Random Foe
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