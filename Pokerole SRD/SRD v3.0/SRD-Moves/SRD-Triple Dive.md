---
Accuracy1: Dexterity
Accuracy2: Athletic/Brawl
AddedEffects: {}
Attributes:
  AccuracyReduction: -1
  TripleAction: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user performs a triple dive jump with perfect timing. The foe is
  washed away by each water splash.
Effect: Single Target. Low Accuracy 1. Triple Action.
Name: Triple Dive
Power: 2
Target: Foe
Type: Water
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