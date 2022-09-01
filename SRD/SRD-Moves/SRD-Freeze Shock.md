---
Accuracy1: SPECIAL
Accuracy2: CHANNEL
Damage1: STRENGTH
Damage2: ''
Description: The user appears to become a block of ice, then it releases itself from
  the ice with a devastating discharge. The exploding ice shards and the lightning
  fly all over the battlefield.
DmgType: PHYSICAL
Effect: Lethal. Ranged. Charge Move. Roll 3 Chance Dice to Paralyze the Foe. -1 Accuracy.
Name: Freeze Shock
Power: 6
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