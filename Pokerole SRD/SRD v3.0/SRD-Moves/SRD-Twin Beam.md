---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects: {}
Attributes:
  DoubleAction: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon shoots a beam, and as if had a mind of its own, another\
  \ part of their body also shoots a beam along."
Effect: Single Target. Double Action.
Name: Twin Beam
Power: 2
Target: Foe
Type: Psychic
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