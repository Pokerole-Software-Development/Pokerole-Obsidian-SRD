---
Accuracy1: VITALITY
Accuracy2: NATURE
Damage1: ''
Damage2: ''
Description: The user falls asleep. During this period the body benefits from a super
  accelerated healing process.
DmgType: SUPPORT
Effect: Complete Heal. If successful spend 1 Will point to activate. The User must
  Sleep for a whole Round (from Round Start to Round End).
Name: Rest
Power: 0
Target: User
Type: Psychic
---

#PokeroleSRD/Moves

## `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`