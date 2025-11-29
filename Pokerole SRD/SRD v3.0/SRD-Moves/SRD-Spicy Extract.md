---
Accuracy1: Clever
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: 2
    Stats:
    - Strength
  - Affects: Targets
    Stages: -2
    Stats:
    - Def
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user dares their victim to eat a hot pepper, out of pride, the foe
  does and suffers as the pepper was double-loaded with spicy extract.
Effect: Single Target. Increase the Target's Strength by 2. Reduce the Target's Defense
  by 2.
Name: Spicy Extract
Power: 0
Target: Foe
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