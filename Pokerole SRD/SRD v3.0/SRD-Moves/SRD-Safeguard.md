---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Safeguard
Attributes:
  Duration: 4
Category: Support
Damage1: ''
Damage2: ''
Description: A force field covers half of the battlefield and filters out all impurities
  and ill intentions coming from the other side.
Effect: Target User's side of the Field. Force Field. Those affected are immune to
  all Status Ailements/Conditions. Previously inflicted Status Ailments/Conditions
  remain. Duration 4 Rounds.
Name: Safeguard
Power: 0
Target: Ally's Battlefield
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