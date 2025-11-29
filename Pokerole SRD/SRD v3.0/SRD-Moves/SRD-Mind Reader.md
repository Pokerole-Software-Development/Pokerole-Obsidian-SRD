---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: MindReader
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "In a split of second, the Pok\xE9mon reads the foe\u2019s mind so they\
  \ know exactly what to do next."
Effect: Single Target. The User has 2 automatic and unremovable successes on the next
  Accuracy or Evasion Roll against the Target.
Name: Mind Reader
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