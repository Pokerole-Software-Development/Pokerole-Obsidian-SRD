---
Accuracy1: Special
Accuracy2: Perform
AddedEffects: {}
Attributes: {}
Damage1: Special
Damage2: ''
Description: The user attacks the foe with a song. If a teammate joins the song the
  attack will be stronger.
DmgType: Special
Effect: If the User and an Ally are able to use Round, then both may choose to do
  it at the same time. If they do, both Pokemon add 3 Dice to the Damage Roll.
Name: Round
Power: 2
Target: Foe
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