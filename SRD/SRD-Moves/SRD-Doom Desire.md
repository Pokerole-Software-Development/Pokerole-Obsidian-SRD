---
Accuracy1: INSIGHT
Accuracy2: ALLURE
Damage1: SPECIAL
Damage2: ''
Description: Be careful what you wish for, this Pokemon will read your most intimate
  wishes and make them come true in very twisted ways.
DmgType: SPECIAL
Effect: Strikes at the end of the Round after the next. Bypass Shield Moves and Cover.
  If the target retires or switches out from battle, the damage will be dealt to the
  next opponent or to one of its allies. Extra effects may be added at Storyteller's
  Discretion
Name: Doom Desire
Power: 6
Target: Foe
Type: Steel
---

#PokeroleSRD/Moves

## `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`