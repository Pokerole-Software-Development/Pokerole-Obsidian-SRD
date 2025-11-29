---
Accuracy1: Insight
Accuracy2: Channel/Perform
AddedEffects: {}
Attributes:
  SoundMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: The user screeches or sings at such high frequencies that anything made
  of glass will break. The ears of the victims are left in no better state.
Effect: Target All Foes in Range. Sound Move.
Name: Hyper Voice
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