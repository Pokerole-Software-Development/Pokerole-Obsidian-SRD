---
Accuracy1: Dexterity
Accuracy2: Athletic
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Paralyze
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon rides a wave charged with electricity. It looks incredibly\
  \ rad but it is also dangerous, as electrified water is not considered safe for\
  \ surfing."
Effect: Target All Foes in Range. Roll 3 Chance Dice to Paralyze those affected. If
  the user of this Move is at its Final Stage of Evolution, this move fails.
Name: Splishy Splash
Power: 3
Target: All Foes
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