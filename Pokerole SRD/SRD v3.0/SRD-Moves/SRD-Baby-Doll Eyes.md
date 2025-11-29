---
Accuracy1: Cute
Accuracy2: Charm
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -1
    Stats:
    - Strength
Attributes:
  Reaction: '1'
Category: Support
Damage1: ''
Damage2: ''
Description: "The biggest and brightest eyes, spakling with unshed tears, how can\
  \ you say \u201Cno\u201D to that?!"
Effect: Single Target. Reaction 1. Reduce Target's Strength by 1.
Name: Baby-Doll Eyes
Power: '0 '
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