---
Accuracy1: Vitality
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  Priority: 3
  ShieldMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon uses its whole body to provide coverage and protection to
  its allies against an incoming attack.
Effect: Priority 3. Shield. Reduce 3 Damage the User and Allies would receive from
  a damaging move. Reduce to zero the set damage from a move the User and Allies would
  take.
Name: Wide Guard
Power: 0
Target: User and Allies
Type: Rock
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