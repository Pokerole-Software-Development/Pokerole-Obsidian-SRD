---
Accuracy1: Vitality
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: 1
    Stats:
    - Strength
    - Special
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon performs a basic manteniance on their ally. A change\
  \ of oil and filters, new spark plugs, and the ally is more than ready!"
Effect: Target One Ally. Increase by 1 the Strength and Spcial of one Steel-Type of
  Electric-Type Ally.
Name: Gear Up
Power: 0
Target: Ally
Type: Steel
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