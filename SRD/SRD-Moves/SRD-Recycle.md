---
Accuracy1: Vitality
Accuracy2: Nature
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: One Pokemon's trash is another one's treasure.
Effect: The Pokemon reuses an Item that has already been spent. (Berries etc.) An
  Item may not be recycled more than 5 times.
Name: Recycle
Power: 0
Target: User
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