---
Accuracy1: Will
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Endure
Attributes:
  Priority: 5
  ShieldMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: The user gets prepared to receive a fatal blow. It resists the pain despite
  being seriously hurt.
Effect: Priority 5. Shield Move. For the rest of the Round damaging moves can not
  reduce the user's HP to less then 1. Status Ailments, Weather Conditions, Recoil,
  Self inflicted damage can still deal damage.
Name: Endure
Power: 0
Target: User
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