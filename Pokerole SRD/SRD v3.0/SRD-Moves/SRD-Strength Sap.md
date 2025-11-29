---
Accuracy1: Vitality
Accuracy2: Nature
AddedEffects:
  Heal:
    Target: User
    Type: Basic
    WillPointCost: 1
  StatChanges:
  - Affects: Targets
    Stages: -1
    Stats:
    - Strength
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon looks for a weak point on its foe, then feeds on its\
  \ vital energy. The foe is left feeling feeble."
Effect: Single Target. Reduce Target's Strength by 1. Heal 1 HP to the user. If successful,
  spend 1 Will Point to activate.
Name: Strength Sap
Power: 0
Target: Foe
Type: Grass
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