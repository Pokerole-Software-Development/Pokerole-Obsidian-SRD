---
Accuracy1: VITALITY
Accuracy2: BRAWL
Damage1: ''
Damage2: ''
Description: The Pokemon uses its whole body to provide coverage and protection to
  its allies against an incoming attack.
DmgType: SUPPORT
Effect: Priority 3. Shield. Reduce 3 Damage the User and Allies would receive from
  a damaging move. Reduce to zero the set damage from a move the User and Allies would
  take.
Name: Wide Guard
Power: 0
Target: User and Allies
Type: Rock
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