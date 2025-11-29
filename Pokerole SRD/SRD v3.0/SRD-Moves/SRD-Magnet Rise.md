---
Accuracy1: Insight
Accuracy2: Athletic
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Float
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon creates a magnetic field to repel themselves from the\
  \ ground, allowing it to float for a short period of time."
Effect: Target Self. The User gains Immunity against Ground-Type Moves. Whole Scene
  Duration
Name: Magnet Rise
Power: 0
Target: Self
Type: Electric
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