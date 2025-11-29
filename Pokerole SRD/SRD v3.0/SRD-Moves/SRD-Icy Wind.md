---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -1
    Stats:
    - Dexterity
Attributes:
  WindMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: Polar winds sweep through the arena. Everyone starts to shiver and embrace
  themselves, trying to preserve a bit of warmth.
Effect: Target All Foes in Range. Wind Move. Reduce by 1 the Dexterity of those affected.
Name: Icy Wind
Power: 2
Target: All Foes
Type: Ice
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