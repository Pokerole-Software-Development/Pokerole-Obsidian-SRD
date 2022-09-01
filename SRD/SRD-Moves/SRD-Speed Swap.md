---
Accuracy1: SPECIAL
Accuracy2: CHANNEL
Damage1: ''
Damage2: ''
Description: The Pokemon employs its psychic power to make the opponent perceive events
  as if they were happening faster or slower according to the user's own speed.
DmgType: SUPPORT
Effect: Switch your Dexterity with your Foe.
Name: Speed Swap
Power: 0
Target: Foe
Type: Psychic
---

#PokeroleSRD/Moves

## `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`