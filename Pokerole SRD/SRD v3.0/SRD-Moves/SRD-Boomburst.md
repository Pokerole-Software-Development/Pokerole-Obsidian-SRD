---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  SoundMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon creates a sudden explosive sound that deafens everyone\
  \ around."
Effect: Area Move. Sound Move.
Name: Boomburst
Power: 6
Target: Area
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