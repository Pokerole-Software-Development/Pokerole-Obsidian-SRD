---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: GlitzyGlow
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: The user surrounds itself with a glamorous light, releasing it as a psychic
  blast, the soft glowing particles remain in the field protecting its fabulousness.
Effect: If successful, for the next 4 Rounds the User and Allies will receive 1 less
  damage from Special Attacks. This effect does not stack. If the user of this Move
  is at its Final Stage of Evolution, this move fails.
Name: Glitzy Glow
Power: 3
Target: Foe
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