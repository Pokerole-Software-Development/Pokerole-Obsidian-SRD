---
Accuracy1: Strength
Accuracy2: Channel
AddedEffects: {}
Attributes:
  AccuracyReduction: 2
  HighCritical: true
  Lethal: true
  PhysicalRanged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user hurls sharp stones at the foe. The speed and weight of the stones
  deals a severe amount of damage.
Effect: Ranged. High Critical. Lethal. -2 Accuracy.
Name: Stone Edge
Power: 4
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