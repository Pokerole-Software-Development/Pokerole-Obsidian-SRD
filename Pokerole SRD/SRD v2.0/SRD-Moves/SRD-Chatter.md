---
Accuracy1: Insight
Accuracy2: Perform
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Confuse
Attributes:
  SoundBased: true
Category: Special
Damage1: Special
Damage2: ''
Description: The user starts talking and giving orders in human language. It may be
  extremely confusing for the foes.
Effect: Roll 3 Chance Dice to Confuse the foe. Sound based move.
Name: Chatter
Power: 2
Target: Foe
Type: Flying
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