---
Accuracy1: Will
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Duration: wholeScene
  Unique: true
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon modifies their own DNA structure and becomes an identical\
  \ clone to any Pok\xE9mon, creature or object it can see. Some clones keep their\
  \ funny eyes."
Effect: Target Self. Unique Move. The User transforms into a copy of a chosen Target.
  It has the same Ability, Attributes, Attribute Increases and Reductions, and Moves,
  keeping Transform. Whole Scene Duration.
Name: Transform
Power: 0
Target: Self
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