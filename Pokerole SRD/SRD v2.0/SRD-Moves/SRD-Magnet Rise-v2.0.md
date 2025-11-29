---
Accuracy1: Insight
Accuracy2: Nature
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Float
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon uses the magnetic field of the earth to repel itself from
  the ground, allowing it to float for a short period of time.
Effect: For the Next 4 Rounds the User gains immunity against Ground Type Moves.
Name: Magnet Rise
Power: 0
Target: User
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