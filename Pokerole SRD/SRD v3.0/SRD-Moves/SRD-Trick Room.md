---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Duration: 4
Category: Support
Damage1: ''
Damage2: ''
Description: "Reality inside the battlefielfield is distorted, time bends and flows\
  \ differently for everyone. Those who don\u2019t rush through manage to adapt easier."
Effect: Target the Battlefield. Invert the order of Initiative. Duration 4 Rounds.
Name: Trick Room
Power: 0
Target: Battlefield
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