---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Poison
Attributes:
  AccuracyReduction: 2
  PhysicalRanged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The Pokemon shoots a stream of corrosive sludge made with the most toxic
  substances it can produce. Just inhaling the scent can make you feel very sick.
Effect: Ranged. Roll 3 Chance Dice to Poison the Foe. -2 Accuracy.
Name: Gunk Shot
Power: 5
Target: Foe
Type: Poison
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