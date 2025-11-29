---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: User
    ChanceDice: 1
    Stages: 1
    Stats:
    - Strength
    - Dexterity
    - Special
    - Def
    - SpDef
Attributes:
  WindMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: The battlefield gets absolutely silent, the only noise is a cold wind
  draft that gives the target chills and goosebumps. Observing from the shadows, the
  user rejoices in the fear.
Effect: Single Target. Wind Move. Roll 1 Chance Die to Increase by 1 the User's Strength,
  Dexterity, Special, Defense and Sp. Defense.
Name: Ominous Wind
Power: 2
Target: Foe
Type: Ghost
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