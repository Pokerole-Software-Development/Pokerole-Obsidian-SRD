---
Accuracy1: Insight
Accuracy2: Intimidate
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -1
    Stats:
    - Special
Attributes:
  SoundMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon viciously snarls showing its teeth to the foes. This\
  \ menacing look will make everyone cower in fear."
Effect: Target all foes in Range. Sound Move. Reduce by 1 the Special of those affected
Name: Snarl
Power: 2
Target: All Foes
Type: Dark
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