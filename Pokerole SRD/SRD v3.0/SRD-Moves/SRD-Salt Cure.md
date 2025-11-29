---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Duration: 4
  OngoingDamage: true
  Ranged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user covers the foe with a salt crust, the salt irritates the skin
  and drehydrates the victim. It can even rust metal in a few seconds.
Effect: Single Target. Ranged. Ongoing Damage. Duration 4 Rounds. Steel-Type and Water-Type
  Pokemon receive Super-Effective Damage from this Move and 1 Extra Damage from the
  Ongoing Damage.
Name: Salt Cure
Power: 2
Target: Foe
Type: Rock
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