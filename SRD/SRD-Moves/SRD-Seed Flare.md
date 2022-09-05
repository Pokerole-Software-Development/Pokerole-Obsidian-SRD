---
Accuracy1: Special
Accuracy2: Channel
Damage1: Special
Damage2: ''
Description: Shaymin releases an explosion of pollen and seeds that the foe cannot
  shake off, leaving it vulnerable. Over time, these seeds will grow into gigantic
  trees of life.
DmgType: Special
Effect: Lethal. Roll 4 Chance Dice to Reduce the foe's Sp. Defense by 2.
Name: Seed Flare
Power: 5
Target: Foe
Type: Grass
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