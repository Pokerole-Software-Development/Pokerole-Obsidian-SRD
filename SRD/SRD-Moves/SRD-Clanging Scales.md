---
Accuracy1: Dexterity
Accuracy2: Perform
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: -1
    Stats:
    - Def
Attributes:
  SoundBased: true
Damage1: Special
Damage2: ''
Description: The Pokemon rattles the scales of its armor creating a frightening noise
  in the area. Some of its scales fall of as a result, leaving some areas exposed.
DmgType: Special
Effect: Sound Based. Reduce User's Defense.
Name: Clanging Scales
Power: 4
Target: All Foes
Type: Dragon
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