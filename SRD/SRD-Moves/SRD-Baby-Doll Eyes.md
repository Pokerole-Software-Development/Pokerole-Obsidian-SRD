---
Accuracy1: Cute
Accuracy2: Allure
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -1
    Stats:
    - Strength
Attributes:
  Priority: 1
Category: Support
Damage1: ''
Damage2: ''
Description: Before anyone acts in battle, the user looks at the foe with the cutest
  eyes.
Effect: Priority 1. Reduce foe's Strength.
Name: Baby-Doll Eyes
Power: 0
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