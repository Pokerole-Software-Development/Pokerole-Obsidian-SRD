---
Accuracy1: DEXTERITY
Accuracy2: BRAWL
Damage1: STRENGTH
Damage2: ''
Description: The Pokemon gets ready to release a boiling gas through its beak, which
  gets incredibly hot. The resulting blast sounds like a train's horn.
DmgType: PHYSICAL
Effect: Ranged. Charge Move. Low Priority 3. If the User is hit by a Non Ranged Physical
  Attack while this move is charging, apply Burn 2 to the foe.
Name: Beak Blast
Power: 4
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