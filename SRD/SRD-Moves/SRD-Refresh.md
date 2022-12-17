---
Accuracy1: Will
Accuracy2: Channel
AddedEffects:
  AilmentHeal:
  - Burn1
  - Burn2
  - Burn3
  - Paralysis
  - Poison
Attributes: {}
Damage1: ''
Damage2: ''
Description: The Pokemon takes a few seconds to cool down and get back in the game.
DmgType: Support
Effect: The User cure itself from Poison, Burn, or Paralysis.
Name: Refresh
Power: 0
Target: User
Type: Normal
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`