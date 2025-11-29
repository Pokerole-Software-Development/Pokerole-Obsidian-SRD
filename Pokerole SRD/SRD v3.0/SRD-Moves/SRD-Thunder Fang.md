---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 2
    Type: Flinch
  - Affects: Targets
    ChanceDice: 2
    Type: Paralyze
Attributes:
  AccuracyReduction: -1
  BiteMove: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon bites the foe with charged fangs, basically injecting\
  \ electricity right into the foe\u2019s nervous system."
Effect: Single Target. Low Accuracy 1. Bite Move. Roll 2 Chance Dice to Flinch the
  Target. Roll 2 Chance Dice to Paralyze the Target.
Name: Thunder Fang
Power: 2
Target: Foe
Type: Electric
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