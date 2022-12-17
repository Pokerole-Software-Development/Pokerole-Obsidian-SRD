---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Lethal: true
Damage1: Special
Damage2: ''
Description: The Pokemon sets ablaze a swirling pillar upon the target, said pillar
  will grow taller and swirl faster if there's a special kind of charge nearby.
DmgType: Special
Effect: "Lethal. If the Move \u201CFusion Bolt\u201D has already been used by anyone\
  \ this Round, add 4 Extra Dice to the Damage Pool of this Move"
Name: Fusion Flare
Power: 4
Target: Foe
Type: Fire
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`