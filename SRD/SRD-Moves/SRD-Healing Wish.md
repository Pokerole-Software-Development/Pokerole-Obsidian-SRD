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
Description: The power of ultimate love and sacrifice. The user wishes to completely
  heal all injuries, diseases, and ailments to save someone's life at the cost of
  their own health.
Effect: The User faints. One Ally is completely healed from all damage and status
  ailments.
Name: Healing Wish
Power: 0
Target: One Ally
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