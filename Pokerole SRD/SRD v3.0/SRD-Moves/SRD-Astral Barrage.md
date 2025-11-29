---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Lethal: true
  Unique: true
Category: Special
Damage1: Special
Damage2: ''
Description: Call upon the restless spirits of the dead and send them to destroy your
  opponents. A truly frightening sight to witness.
Effect: Target All Foes in Range. Lethal. Unique.
Name: Astral Barrage
Power: 5
Target: All Foes
Type: Ghost
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