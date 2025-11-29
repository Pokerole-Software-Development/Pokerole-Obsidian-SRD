---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  Ailments:
  - Affects: Targets
    Rounds: 4
    Type: AquaRingLifeDew
Attributes:
  Duration: 4
Category: Support
Damage1: ''
Damage2: ''
Description: The user creates a fresh-water dew that restores energy and heals wounds.
Effect: Target User and Allies in Range. If successful, spend 1 Will point to activate.
  User and Allies in Range heal 1 HP at the end of each Round. Duration 4 Rounds.
Name: Life Dew
Power: 0
Target: All Allies
Type: Water
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