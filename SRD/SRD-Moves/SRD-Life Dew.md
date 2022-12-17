---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  Ailments:
  - Affects: Target
    Rounds: 4
    Type: AquaRingLifeDew
Attributes: {}
Damage1: ''
Damage2: ''
Description: The user creates a fresh-water dew that makes it and its allies full
  of energy.
DmgType: Support
Effect: If successful, spend 1 Will point to activate. User and Allies in Range heal
  1 HP at the end of each Round. Lasts 4 Rounds.
Name: Life Dew
Power: 0
Target: User and Allies
Type: Water
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`