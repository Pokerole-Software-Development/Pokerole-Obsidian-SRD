---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: User
    Type: SpeedSwap
  - Affects: Target
    Type: SpeedSwap
Attributes: {}
Damage1: ''
Damage2: ''
Description: The Pokemon employs its psychic power to make the opponent perceive events
  as if they were happening faster or slower according to the user's own speed.
DmgType: Support
Effect: Switch your Dexterity with your Foe.
Name: Speed Swap
Power: 0
Target: Foe
Type: Psychic
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