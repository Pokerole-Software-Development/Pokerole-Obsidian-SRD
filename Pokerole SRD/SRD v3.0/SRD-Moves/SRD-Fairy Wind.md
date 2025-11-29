---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  WindMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon let\u2019s out sweet a breeze of glittery fairy dust.\
  \ It gives a mild rash to those without happy thoughts."
Effect: Single Target. Wind Move.
Name: Fairy Wind
Power: 2
Target: Foe
Type: Fairy
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