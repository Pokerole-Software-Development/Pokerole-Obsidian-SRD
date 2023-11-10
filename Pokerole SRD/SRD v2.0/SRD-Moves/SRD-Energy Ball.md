---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Targets
    ChanceDice: 1
    Stages: -1
    Stats:
    - SpDef
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: The Pokemon gathers nature's energy in a ball and hurls it at the foe.
  Trees and bushes may be left opaque and sad.
Effect: Roll 1 Chance Dice to Reduce foe's Sp. Defense.
Name: Energy Ball
Power: 3
Target: Foe
Type: Grass
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