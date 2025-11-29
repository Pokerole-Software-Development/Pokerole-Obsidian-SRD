---
Accuracy1: Insight
Accuracy2: Alert
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: IonDeluge
Attributes:
  Duration: wholeScene
Category: Support
Damage1: ''
Damage2: ''
Description: The user electrifies all the particles in the environment with shocking
  results!
Effect: Target Battlefield. Damage from Normal-Type Moves will be considered to be
  Electric-Type. Whole Scene Duration.
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