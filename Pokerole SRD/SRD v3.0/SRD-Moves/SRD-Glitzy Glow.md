---
Accuracy1: Special
Accuracy2: Etiquette
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: GlitzyGlow
Attributes:
  Duration: 4
  ForceField:
    DamageReduction: 1
    DamageType: special
Category: Special
Damage1: Special
Damage2: ''
Description: The user surrounds themselves with a glamorous light and shoots a psychic
  blast, the glowing particles remain in the field protecting their fabulousness.
Effect: Single Target. After dealing damage, activate a Force Field against Special
  Damage with a Duration of 4 Rounds on the User's side of the Field. If the user
  of this Move is at its Final Stage of Evolution, this move fails.
Name: Glitzy Glow
Power: 3
Target: Foe
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