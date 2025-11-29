---
Accuracy1: Vitality
Accuracy2: Stealth
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: ShellTrap
Attributes:
  LateReaction: '3'
  Lethal: true
  Ranged: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon apparently just buries underground, but secretly prepares\
  \ their shell to detonate; anyone who steps on it will be blown to pieces."
Effect: Single Target. Lethal. Late Reaction 3. This Move's damage is only rolled
  the next time the User is hit with a Non-Ranged Physical attack.
Name: Shell Trap
Power: 6
Target: Foe
Type: Fire
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