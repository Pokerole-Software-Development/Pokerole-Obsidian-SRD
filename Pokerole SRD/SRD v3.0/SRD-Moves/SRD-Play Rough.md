---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects:
  StatChanges:
  - Affects: Targets
    ChanceDice: 1
    Stages: -1
    Stats:
    - Strength
Attributes:
  AccuracyReduction: -1
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon and their foe start a playful wrestle that soon escalates\
  \ into a furious wrestling match."
Effect: Single Target. Low Accuracy 1. Roll 1 Chance Dice to Reduce Target's Strength
  by 1.
Name: Play Rough
Power: 3
Target: Foe
Type: Fairy
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