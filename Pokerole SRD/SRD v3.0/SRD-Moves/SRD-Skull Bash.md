---
Accuracy1: Vitality
Accuracy2: Stealth
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: 1
    Stats:
    - Def
Attributes:
  Charge: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user withdraws into their shell, after a few seconds of them not
  moving, the foe goes to inspect and the user pops their head out in in a devastating
  strike.
Effect: Single Target. Charge Move. While this Move is charging, Increase the User's
  Defense by 1.
Name: Skull Bash
Power: 5
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