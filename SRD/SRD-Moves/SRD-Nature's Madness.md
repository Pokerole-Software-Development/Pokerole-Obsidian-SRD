---
Accuracy1: INSIGHT
Accuracy2: NATURE
Damage1: ''
Damage2: ''
Description: The forces of nature attack as if they had a will of their own. Water
  will try to drown you, plants will trap you, lightning will come out of nowhere,
  and even your own body will fail you.
DmgType: SPECIAL
Effect: Damage Roll is Half of the Foe's remaining HP (up to 10) Rounded down. If
  the remaining HP of the foe is 1, this move fails. Ignore the foe's Defenses. -1
  Accuracy.
Name: Nature's Madness
Power: 0
Target: Foe
Type: Fairy
---

#PokeroleSRD/Moves

## `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`