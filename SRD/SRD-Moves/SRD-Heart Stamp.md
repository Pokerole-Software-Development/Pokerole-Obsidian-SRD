---
Accuracy1: Insight
Accuracy2: Allure
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Flinch
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: This move controls the emotions of the target, making it feel loved and
  safe. The user may strike immediately.
Effect: Roll 3 Chance Dice to Flinch the foe.
Name: Heart Stamp
Power: 2
Target: Foe
Type: Psychic
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