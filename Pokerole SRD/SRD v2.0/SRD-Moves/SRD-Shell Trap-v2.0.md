---
Accuracy1: Dexterity
Accuracy2: Stealth
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: ShellTrap
Attributes:
  Priority: -3
Category: Special
Damage1: Special
Damage2: ''
Description: It apparently just buries underground, but secretely the Pokemon prepares
  its shell to detonate; anyone who steps on it will be blown to pieces.
Effect: Low Priority 3. This Move strikes the next time the user is hit with a Non-Ranged
  Physical attack.
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