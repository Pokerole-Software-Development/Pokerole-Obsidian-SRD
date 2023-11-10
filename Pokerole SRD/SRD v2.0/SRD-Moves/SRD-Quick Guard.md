---
Accuracy1: Dexterity
Accuracy2: Athletic
AddedEffects: {}
Attributes:
  Priority: 3
  ShieldMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: The user reacts instinctively and defends itself and its teammates, nullifying
  the effects of the fastest attacks.
Effect: Priority 3. Shield Move. This move will only protect against Damaging Moves
  with "Priority". Reduce 3 Dice from the foe's Damage Pool. Negate the effects of
  support moves that target the User and Allies.
Name: Quick Guard
Power: 0
Target: User and Allies
Type: Fighting
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