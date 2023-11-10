---
Accuracy1: Insight
Accuracy2: Nature
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: IonDeluge
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user amplifies all electrically charged particles in the environment.
  The results are shocking!
Effect: For the rest of the Scene, Normal Type Moves will deal damage as if they were
  Electric Type Moves.
Name: Ion Deluge
Power: 0
Target: Battlefield
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