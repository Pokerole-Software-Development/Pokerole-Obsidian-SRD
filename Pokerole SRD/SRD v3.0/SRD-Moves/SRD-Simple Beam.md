---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: SimpleBeam
Attributes:
  AbilityChange: true
  Duration: wholeScene
Category: Support
Damage1: ''
Damage2: ''
Description: "A weak mental beam that doesn\u2019t hurt or confuse the target but\
  \ it does change their view of life as they start to take a simpler apporach to\
  \ things."
Effect: Single Target. Change the Target's Ability to "Simple". Whole Scene Duration.
  This effect does not end by switching out the affected Pokemon.
Name: Simple Beam
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