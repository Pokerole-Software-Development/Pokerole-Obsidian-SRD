---
Accuracy1: Will
Accuracy2: ''
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon prays to the skies with such selfless fervor and devotion\
  \ that a miracle is granted."
Effect: Target One Ally. The User must spend all of their remaining Will points, if
  the user has no remaining Will points, this Move fails. Restore conciousness and
  2 HP to a fainted ally. If no Ally is fainted this Move fails. The ally does not
  need to be active in combat.
Name: Revival Blessing
Power: 0
Target: Ally
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