---
Accuracy1: Tough
Accuracy2: Intimidate
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -1
    Stats:
    - Strength
    - Special
Attributes:
  SwitcherMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: The user threatens the foe, leaving it too scared to pursuit the user
  or overwhelm the ally that just switched in the battlefield.
Effect: Reduce foe's Strength and Special. The user switches out, the new Pokemon
  arrives ready to fight. Roll for its initiative. Switcher Move.
Name: Parting Shot
Power: 0
Target: Foe
Type: Dark
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