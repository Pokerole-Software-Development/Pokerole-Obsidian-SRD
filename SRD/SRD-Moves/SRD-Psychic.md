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
Damage1: Special
Damage2: ''
Description: The user's telekinetic force is enough to cause severe harm to their
  target. This telekinesis is not subtle.
DmgType: Special
Effect: Roll 1 Chance Dice to Reduce the foe's Sp. Defense.
Name: Psychic
Power: 3
Target: Foe
Type: Psychic
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