---
Accuracy1: Insight
Accuracy2: Nature
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -1
    Stats:
    - Strength
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon looks for a weak spot on its foe, then feeds on its vital
  energy. The foe is left feeling feeble.
Effect: Reduce Foe's Strength. User Heals HP equal to the Foe's Current Strength Score.
  Healing in-battle limitations apply.
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