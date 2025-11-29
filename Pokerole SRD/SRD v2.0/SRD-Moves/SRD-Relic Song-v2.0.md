---
Accuracy1: Special
Accuracy2: Perform
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 1
    Type: Sleep
Attributes:
  SoundBased: true
Category: Special
Damage1: Special
Damage2: ''
Description: The user sings and dances to a melody so beautiful you won't notice you
  were crying while listening to it.
Effect: Sound Based. Roll 1 Die to put the foe to Sleep. If successful, the User may
  choose to change its form afterwards.
Name: Relic Song
Power: 2
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