---
Accuracy1: Tough/Cool
Accuracy2: Intimidate
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Confuse
  StatChanges:
  - Affects: Targets
    Stages: 2
    Stats:
    - Strength
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon\u2019s arrogant and mocking attitude enrage their foe\
  \ and make it lose focus in battle."
Effect: Single Target. Increase the Target's Strength by 2. Confuse the Target.
Name: Swagger
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