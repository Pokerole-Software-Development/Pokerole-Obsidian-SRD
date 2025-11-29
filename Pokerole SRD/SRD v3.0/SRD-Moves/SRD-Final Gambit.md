---
Accuracy1: Will
Accuracy2: Brawl/Athletic
AddedEffects: {}
Attributes:
  IgnoreDefenses: true
  UserFaints: true
Category: Special
Damage1: Target'sRemainingHP
Damage2: ''
Description: "The Pok\xE9mon puts its last Strength into an all-or-nothing attack.\
  \ After that, the user faints."
Effect: Single Target. Ignore Defenses. The user Faints after dealing Damage.
Name: Final Gambit
Power: 4
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