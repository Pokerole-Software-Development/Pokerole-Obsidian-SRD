---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  AccuracyReduction: 1
  Priority: -1
  SwitcherMove: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user throws the target 60 feet out of the battlefield.
Effect: Low Priority 1. The target is hit and knocked back to its trainer forcing
  them to send out another Pokemon. In the wild the target is sent away. Switcher
  Move. -1 Accuracy.
Name: Circle Throw
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