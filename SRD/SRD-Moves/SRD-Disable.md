---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Disable
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user hits a nerve on the foe, impeding it from performing its previous
  action for a short while.
Effect: The Target cannot use the last move it performed. Lasts 4 Rounds.
Name: Disable
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