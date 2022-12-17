---
Accuracy1: Special
Accuracy2: Perform
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Flinch
Attributes:
  SoundBased: true
Damage1: Special
Damage2: ''
Description: After falling asleep the user lets out a powerful snore, disrupting any
  focus the foe had.
DmgType: Special
Effect: This move can only be used if the user asleep. Roll 3 Chance Dice to Flinch
  the foe. Sound Based Move.
Name: Snore
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