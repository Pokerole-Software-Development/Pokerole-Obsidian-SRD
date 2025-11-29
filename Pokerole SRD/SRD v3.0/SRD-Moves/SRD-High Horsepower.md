---
Accuracy1: Vitality
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  AccuracyReduction: -1
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon tramples their foe without mercy. Their powerful body\
  \ could pull a traction vehicle for very long distances."
Effect: Single Target. Low Accuracy 1.
Name: High Horsepower
Power: 4
Target: Foe
Type: Ground
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