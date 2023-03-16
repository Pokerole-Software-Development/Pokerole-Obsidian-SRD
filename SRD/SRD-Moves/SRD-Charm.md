---
Accuracy1: Cute
Accuracy2: Allure
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -2
    Stats:
    - Strength
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon uses a cute and harmless attitude to make the foe less wary
  and aggresive.
Effect: Reduce foe's Strength by 2.
Name: Charm
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