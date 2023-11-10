---
Accuracy1: Will
Accuracy2: Athletic
AddedEffects: {}
Attributes:
  IgnoreDefenses: true
  UserFaints: true
Category: Special
Damage1: ''
Damage2: ''
Description: The Pokemon puts its last strength into an all-or-nothing attack. After
  that, it faints.
Effect: Ignore the foe's Defenses. The user faints after dealing damage.
Name: Final Gambit
Power: 0
Target: Foe
Type: Fighting
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