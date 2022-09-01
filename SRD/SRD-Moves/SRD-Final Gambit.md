---
Accuracy1: WILL
Accuracy2: ATHLETIC
Damage1: ''
Damage2: ''
Description: The Pokemon puts its last strength into an all-or-nothing attack. After
  that, it faints.
DmgType: SPECIAL
Effect: Ignore the foe's Defenses. The user faints after dealing damage.
Name: Final Gambit
Power: 0
Target: Foe
Type: Fighting
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