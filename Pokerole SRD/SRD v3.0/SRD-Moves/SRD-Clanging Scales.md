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
  SoundMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon rattles the scales of its armor creating a frightening\
  \ noise in the area. Some of its scales fall off as a result, leaving some areas\
  \ exposed."
Effect: Target all Foes in Range. Sound Move. Reduce User's Defense by 1.
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

| Type          | Target          | Category          | Power          |
| ------------- | --------------- | ----------------  | -------------- |
| `= this.Type` | `= this.Target` | `= this.Category` | `= this.Power` | 

**Effect:** `= this.Effect`