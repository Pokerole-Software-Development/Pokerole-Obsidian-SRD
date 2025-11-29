---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  AccuracyReduction: -1
  HighCritical: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon uses their powerful claws to beat down any foe. There\u2019\
  s a reason seafood is not too popular in this world."
Effect: Single Target. Low Accuracy 1. High Critical
Name: Crabhammer
Power: 3
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