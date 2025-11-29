---
Accuracy1: Strength
Accuracy2: Stealth
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -1
    Stats:
    - SpDef
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon stalks and strikes the foe, usually from behind bushes\
  \ or any sort of cover."
Effect: Single Target. Reduce the Target's Special by 1.
Name: Skitter Smack
Power: 3
Target: Foe
Type: Bug
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