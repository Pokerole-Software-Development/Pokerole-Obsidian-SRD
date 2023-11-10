---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon mentalizes itself stronger than anyone. They feel good. They
  can win. They. Can. Do. This.
Effect: Copy the Target's Attribute and Trait Modifiers and keep them until the end
  of the scene.
Name: Psych Up
Power: 0
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