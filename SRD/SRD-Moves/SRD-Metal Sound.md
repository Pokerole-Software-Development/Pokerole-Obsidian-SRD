---
Accuracy1: TOUGH
Accuracy2: PERFORM
Damage1: ''
Damage2: ''
Description: The user produces a horrible noise that impedes the foe from focusing
  on the fight, leaving it vulnerable to attacks.
DmgType: SUPPORT
Effect: Sound Based. Reduce the foe's Special Defense by 2.
Name: Metal Sound
Power: 0
Target: Foe
Type: Steel
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