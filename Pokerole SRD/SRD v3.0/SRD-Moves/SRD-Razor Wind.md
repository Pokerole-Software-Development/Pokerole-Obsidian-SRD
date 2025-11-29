---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Charge: true
  CutterMove: true
  HighCritical: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon sways the winds while charging what appears to be an\
  \ invisible blade made of pressurized air. The wind slices everything it touches\
  \ as if it were a razor."
Effect: Target All Foes in Range. Charge Move. High Critical. Cutter Move.
Name: Razor Wind
Power: 3
Target: All Foes
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