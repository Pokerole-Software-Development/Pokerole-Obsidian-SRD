---
Accuracy1: DEXTERITY
Accuracy2: CHANNEL
Damage1: SPECIAL
Damage2: HAPPINESS
Description: The User lets out its energy in the form of a lightning strike, the happier
  the user feels the more energized it will be.
DmgType: SPECIAL
Effect: Add 1 Die to the Damage Roll for every point of Happiness on the User. If
  the user of this Move is at its Final Stage of Evolution, this move fails.
Name: Pika Papow
Power: 0
Target: Foe
Type: Electric
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