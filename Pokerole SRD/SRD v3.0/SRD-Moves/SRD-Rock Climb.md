---
Accuracy1: Strength
Accuracy2: Athletic
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 2
    Type: Confuse
Attributes:
  AccuracyReduction: -2
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon climbs over the foe and rests atop of their head as if\
  \ it were the top of a mountain. This results confusing for the foe."
Effect: Single Target. Low Accuracy 2. Roll 2 Chance Dice to Confuse the Target. Out
  of battle it aids to climb cliffs and mountains with ease.
Name: Rock Climb
Power: 3
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