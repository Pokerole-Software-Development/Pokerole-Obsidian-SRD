---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  HighCritical: true
Category: Special
Damage1: Special
Damage2: ''
Description: The user shoots a piercing water jet with incredible precision.
Effect: Single Target. High Critical. Ignore effects from Moves, Items or Abilities
  that would prevent this Move from targeting the foe.
Name: Snipe Shot
Power: 3
Target: Foe
Type: Water
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