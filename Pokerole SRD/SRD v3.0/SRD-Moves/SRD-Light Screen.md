---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: LightScreen
Attributes:
  Duration: 4
  ForceField:
    DamageReduction: 1
    DamageType: special
Category: Support
Damage1: ''
Damage2: ''
Description: A barrier of light is created over half of the battlefield, all energy
  trying to go trough dissolves as it crosses it.
Effect: Target the User's side of the field. Force Field. Activate a Force Field against
  Special Damage. Duration 4 Rounds.
Name: Light Screen
Power: 0
Target: Ally's Battlefield
Type: Psychic
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