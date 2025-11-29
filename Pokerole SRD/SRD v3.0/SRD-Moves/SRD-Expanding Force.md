---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Lethal: true
Category: Special
Damage1: Special
Damage2: ''
Description: Psychic energies form a bubble of light to damage the foe. Under Psychic
  Terrain, the energy is so big it turns into a tall pillar that crushes anyone inside.
Effect: Single Target. Lethal. *If Psychic Terrain is active, add 2 Extra Dice to
  the Damage Pool of this Move and you may add another target to it.
Name: Expanding Force
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