---
Accuracy1: Missing beauty
Accuracy2: ALLURE
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Sleep
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon approaches the foe with a kiss. Its ugly face and awful smooch
  make the poor creature faint in terror.
Effect: Put the Target to Sleep.
Name: Lovely Kiss
Power: 0
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