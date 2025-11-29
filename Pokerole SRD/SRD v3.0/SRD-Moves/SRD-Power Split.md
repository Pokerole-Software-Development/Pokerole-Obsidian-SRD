---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: PowerSplit
  - Affects: User
    Type: PowerSplit
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "Through a mental link both Pok\xE9mon are aware of each other strengths,\
  \ which ends up evening the odds."
Effect: Single Target. Average the User's Strength and Special with the Target's,
  rounded down.
Name: Power Split
Power: 0
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