---
Accuracy1: Tough
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Rounds: 4
    Type: Psychic
Attributes:
  Duration: 4
Category: Support
Damage1: ''
Damage2: ''
Description: "Through a massive mental onslaught, the Pok\xE9mon brings back the memories\
  \ of pain on everyone around."
Effect: Area Move. Those affected can't restore HP. Duration 4 Rounds.
Name: Heal Block
Power: 0
Target: Area
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