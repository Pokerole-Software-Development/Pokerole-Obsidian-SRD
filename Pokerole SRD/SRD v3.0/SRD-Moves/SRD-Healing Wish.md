---
Accuracy1: Will
Accuracy2: Channel
AddedEffects:
  AilmentHeal:
  - All
  Heal:
    Target: Targets
    Type: Complete
    WillPointCost: 1
Attributes:
  UserFaints: true
Category: Support
Damage1: ''
Damage2: ''
Description: In a display of true selflessness, the user makes the ultimate sacrifice
  for the well-being of others.
Effect: Target Self. The user faints. One allied Target restores its full HP and it
  is cured from any Status Condition. If the chosen Target is not in-battle, it is
  called out and ready to fight with the same remaining actions as the user.
Name: Healing Wish
Power: 0
Target: Self
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