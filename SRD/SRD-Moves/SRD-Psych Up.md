---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects: {}
Attributes: {}
Damage1: ''
Damage2: ''
Description: The Pokemon mentalizes itself stronger than anyone. They feel good. They
  can win. They. Can. Do. This.
DmgType: Support
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

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`