---
Accuracy1: Clever
Accuracy2: Nature
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "The user begins pushing pressure points on their body to unlock a hidden\
  \ potential they didn\u2019t even knew they had."
Effect: Target Self. Increase by 1 one of the User's Attributes or Traits at Random
  (Strength, Dexterity, Special, Defense, Sp. Defense, Accuracy, Evasion). If this
  Move is used again, the previous Attribute increase is removed.
Name: Acupressure
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