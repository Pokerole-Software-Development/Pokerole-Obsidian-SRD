---
Accuracy1: Special
Accuracy2: Intimidate
AddedEffects:
  Ailments:
  - Affects: User
    Rounds: 4
    Type: BaddyBad
Attributes:
  Duration: 4
  ForceField: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon acts like a thug and channels its own dark aura as protection\
  \ for itself and its allies."
Effect: Single Target. After dealing damage, activate a Force Field against Physical
  Damage with a Duration of 4 Rounds on the User's side of the Field. If the user
  of this Move is at its Final Stage of Evolution, this move fails.
Name: Baddy Bad
Power: 3
Target: Ally's Battlefield
Type: Dark
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