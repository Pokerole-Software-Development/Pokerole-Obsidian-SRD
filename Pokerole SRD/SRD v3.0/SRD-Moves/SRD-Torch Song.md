---
Accuracy1: Special
Accuracy2: Perform
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: 1
    Stats:
    - Special
Attributes:
  SoundMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: Through a sweet melody the foe burns a haunting memory into those who
  harbor ill intent.
Effect: Single Target. Sound Move. Increase the User's Special by 1.
Name: Torch Song
Power: 3
Target: Foe
Type: Fire
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