---
Accuracy1: Beauty
Accuracy2: Perform
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: PerishSong
Attributes:
  SoundBased: true
Category: Support
Damage1: ''
Damage2: ''
Description: A song of mourning and despair that resonates on the minds of anyone
  who listens. Makes you feel like you are on your death bed.
Effect: After three rounds, if any Pokemon who heard the song is not removed from
  battle, it will receive its remaining HP as damage. Sound Based.
Name: Perish Song
Power: 0
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