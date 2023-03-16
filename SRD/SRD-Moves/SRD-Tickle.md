---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -1
    Stats:
    - Strength
    - Def
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon tickles the foe. The laughter really disturbs the foe's fighting
  stance.
Effect: Reduce the foe's Strength and Defense.
Name: Tickle
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