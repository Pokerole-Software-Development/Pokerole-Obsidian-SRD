---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -2
    Stats:
    - Dexterity
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: The Pokemon strikes the foe's legs, leaving it unable to walk normally
  or run.
Effect: Reduce Foe's Dexterity by 2.
Name: Low Sweep
Power: 2
Target: Foe
Type: Fighting
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