---
Accuracy1: Special
Accuracy2: Channel
Damage1: Special
Damage2: ''
Description: A cold reflection of the moon shines upon the target, it doesn't hurt
  physically but those who stare directly into the light simply collapse.
DmgType: Special
Effect: Lethal. If anything on the foe's side would prevent this move from dealing
  damage (Pokemon Type, Abilities, Shield Moves, Weather or Barriers) ignore it. This
  Move cannot be Clashed.
Name: Moongeist Beam
Power: 4
Target: Foe
Type: Ghost
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