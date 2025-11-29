---
Accuracy1: Insight
Accuracy2: Nature
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "The whole field grows flowers and those flowers keep growing on top\
  \ of all Grass-Type Pok\xE9mon in the field, providing a mild cover and protection\
  \ from harm."
Effect: Target battlefield. Increase by 1 the Defense of all Grass-Type Pokemon.
Name: Flower Shield
Power: 0
Target: Battlefield
Type: Fairy
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