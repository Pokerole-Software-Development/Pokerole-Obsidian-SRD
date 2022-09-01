---
Accuracy1: SPECIAL
Accuracy2: CHANNEL
Damage1: SPECIAL
Damage2: ''
Description: The user touches its foe while playing "Freeze!". Surprisingly, the foe
  becomes frozen on a block of ice. Once they realize they were just playing pretend
  the ice dissolves into haze.
DmgType: SPECIAL
Effect: If successful, remove all Increased or Reduced Attributes and Traits the Foe
  may have. If the user of this Move is at its Final Stage of Evolution, this move
  fails. -1 Accuracy.
Name: Freezy Frost
Power: 3
Target: Foe
Type: Ice
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