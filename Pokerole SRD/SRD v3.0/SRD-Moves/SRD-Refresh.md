---
Accuracy1: Special
Accuracy2: Channel/Athletic
AddedEffects:
  AilmentHeal:
  - Burn1
  - Burn2
  - Burn3
  - Paralysis
  - Freeze
  - Poison
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon takes a few seconds to cool off, refocus, and get back\
  \ in the game."
Effect: Target Self. The User heals itself from any Burn, Freeze, Poison and Paralysis.
  Sleep is not healed through this effect.
Name: Refresh
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