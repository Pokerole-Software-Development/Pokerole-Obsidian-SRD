---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Targets
    ChanceDice: 5
    Stages: -1
    Stats:
    - Special
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: The user engulfs its foe with a cloud of mist. This soothing mist keeps
  evil intents from surfacing into the foe's mind.
Effect: Roll 5 Chance Dice to Reduce the foe's Special. This Effect can be repeated
  up to 3 times per Target.
Name: Mist Ball
Power: 2
Target: Foe
Type: Psychic
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