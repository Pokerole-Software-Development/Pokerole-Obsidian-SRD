---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Safeguard
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon creates an energy shield that protects everyone from harm.
Effect: For the next 4 Rounds, the User and its Allies are immune to Status Ailments
  (Burn. Poison. Sleep. Confuse. Freeze. Paralysis). Lasts 4 Rounds. Previously inflicted
  Status Ailments remain.
Name: Safeguard
Power: 0
Target: User and Allies
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