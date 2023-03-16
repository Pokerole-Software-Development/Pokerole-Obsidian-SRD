---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Paralyze
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: The Pokemon rides a giant surge of electricity as if surfing. It looks
  incredibly rad but it is also dangerous, as electricity does not share the same
  properties of water for safe surfing.
Effect: Roll 3 Chance Dice to Paralyze the foe. If the user of this Move is at its
  Final Stage of Evolution, this move fails.
Name: Splishy Splash
Power: 3
Target: Foe
Type: Water
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