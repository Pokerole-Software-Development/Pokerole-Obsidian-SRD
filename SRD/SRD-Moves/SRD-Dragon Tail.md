---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  AccuracyReduction: 1
  Priority: -1
  SwitcherMove: true
Damage1: Strength
Damage2: ''
Description: This Powerful tail strike can knockdown anyone up to 100 feet away!
DmgType: Physical
Effect: Low Priority 1. The target is hit and knocked back to its trainer, stunned.
  Forcing the trainer to send another Pokemon. In the wild the target is sent away.
  Switcher Move. -1 Accuracy.
Name: Dragon Tail
Power: 2
Target: Foe
Type: Dragon
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`