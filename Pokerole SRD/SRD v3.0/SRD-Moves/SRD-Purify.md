---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  AilmentHeal:
  - All
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The target is covered by a gelatinous goo to which every impurity sticks.
  The user then convinces the target eats this goo, and ends up pleasantly surprised
  by the sweet flavor.
Effect: Single Target. Heal a Target's Status Ailment (Burns, Freeze, Paralysis, Poisons,
  Sleep). *If a Status Ailment was healed this way, the User may spend 1 Will point
  to restore 2 HP.
Name: Purify
Power: 0
Target: Foe
Type: Poison
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