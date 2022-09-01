---
Accuracy1: DEXTERITY
Accuracy2: BRAWL
Damage1: STRENGTH
Damage2: ''
Description: With the help of some air balloons, the user jumps up high and falls
  on top of its foe. The use of balloons in-battle is questionable, but the referee
  will allow them.
DmgType: PHYSICAL
Effect: Roll 3 Chance Dice to Flinch the Foe. If the user of this Move is at its Final
  Stage of Evolution, this move fails.
Name: Floaty Fall
Power: 3
Target: Foe
Type: Flying
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