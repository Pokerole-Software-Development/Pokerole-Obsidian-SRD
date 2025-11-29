---
Accuracy1: SameasBaseMove
Accuracy2: ''
AddedEffects: {}
Attributes:
  MaxMove: true
Category: ''
Damage1: SameasBasePower
Damage2: ''
Description: ''
Effect: Target all foes in Range or a Single Max Target. Activate the Effects of Rain
  Weather. (Disregard location) Duration 4 Rounds.
Name: Max Geyser
Power: 2
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