---
Accuracy1: Beauty
Accuracy2: Perform
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: PerishSong
Attributes:
  SoundMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: A song for mourning the departed. Although it sounds beautiful, it fills
  the heart with grief and despair, making the listeners feel as if they were laying
  on their death bed.
Effect: Area Move. Sound Move. Three Rounds after this Move is used, deal damage to
  those affected equal to their remaining HP. Removing from battle prevents this effect.
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