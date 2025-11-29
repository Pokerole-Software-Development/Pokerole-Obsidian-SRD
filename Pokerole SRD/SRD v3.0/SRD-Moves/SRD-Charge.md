---
Accuracy1: Insight
Accuracy2: Alert
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Charge
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user gathers electricity and stores it to make its attacks more powerful.
  You may also use them as a living battery for your phone.
Effect: Target Self. Add 2 Dice to the Damage Pool of thenext Damaging Electric-Type
  Move the User performs.
Name: Charge
Power: 0
Target: Self
Type: Electric
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