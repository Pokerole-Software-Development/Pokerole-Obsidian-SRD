---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: User
    Rounds: 4
    Type: BaddyBad
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: The Pokemon acts like a thug and channels its own dark aura as protection
  for itself and its allies.
Effect: If successful, for the next 4 Rounds the User and Allies will receive 1 less
  damage from Physical Attacks. This effect does not stack. If the user of this Move
  is at its Final Stage of Evolution, this move fails.
Name: Baddy Bad
Power: 3
Target: Foe
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