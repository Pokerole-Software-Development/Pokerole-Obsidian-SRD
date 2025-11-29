---
Accuracy1: Insight
Accuracy2: Alert
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Electrify
Attributes:
  Reaction: '1'
Category: Support
Damage1: ''
Damage2: ''
Description: "The user hurls a sudden electric jolt onto its target. The target\u2019\
  s is now charged and will need to release the excess energy through an attack."
Effect: Single Target. Reaction 1. All Damage of the Next Physical or Special Move
  the Target performs will become Electric-Type
Name: Electrify
Power: 0
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