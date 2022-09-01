---
Accuracy1: SPECIAL
Accuracy2: PERFORM
Damage1: ''
Damage2: ''
Description: The user plays a beautiful and soothing melody that lulls the target
  into a peaceful sleep.
DmgType: SUPPORT
Effect: Sound Based. Put the Target to Sleep. -3 Accuracy.
Name: Grass Whistle
Power: 0
Target: Foe
Type: Grass
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