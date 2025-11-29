---
Accuracy1: Vitality
Accuracy2: Nature
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "After stockpiling, the Pok\xE9mon swallows the energy to restore their\
  \ health, they go back to their normal size afterwards."
Effect: Target Self. The user must have previously used the Move "Stockpile", otherwise
  this Move will fail. Complete Heal, if successful, spend 1 Will point to activate.
  Reduce by 1 the User's Defense and Sp. Defense.
Name: Swallow
Power: 0
Target: Self
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