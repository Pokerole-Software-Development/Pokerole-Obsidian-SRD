---
Accuracy1: Cute
Accuracy2: Charm
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -1
    Stats:
    - Special
Attributes:
  SoundMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon tells a secret to the target. They giggle together but\
  \ the foe loses its concentration on the battle."
Effect: Single Target. Reduce the Target's Special by 1.
Name: Confide
Power: 0
Target: Foe
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