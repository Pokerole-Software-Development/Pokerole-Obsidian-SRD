---
Accuracy1: Dexterity/Strength
Accuracy2: Channel
AddedEffects: {}
Attributes:
  AccuracyReduction: -1
  PhysicalRanged: true
  Ranged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "Back in the day, this was a common form of amusement amongst Pok\xE9\
  mon and children alike."
Effect: Single Target. Low Accuracy 1. Ranged.
Name: Rock Throw
Power: 2
Target: Foe
Type: Rock
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