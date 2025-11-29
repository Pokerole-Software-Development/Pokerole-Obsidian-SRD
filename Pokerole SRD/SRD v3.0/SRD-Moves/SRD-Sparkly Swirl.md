---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  AilmentHeal:
  - All
Attributes:
  AccuracyReduction: -1
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon unleashes a swirling and glittery energy that releases\
  \ a pleasant aroma that soothes the body and has healing properties."
Effect: Single Target. Low Accuracy 1. Heal any Status Ailment on the User and Allies
  in Range. If the user of the Move is at its Final Stage of Evolution, this move
  fails.
Name: Sparkly Swirl
Power: 3
Target: All Allies
Type: Fairy
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