---
Accuracy1: Insight
Accuracy2: Allure
Damage1: Strength
Damage2: ''
Description: This move controls the emotions of the target, making it feel loved and
  safe. The user may strike immediately.
DmgType: Physical
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

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`