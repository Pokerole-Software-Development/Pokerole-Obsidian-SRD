---
Accuracy1: STRENGTH
Accuracy2: BRAWL
Damage1: STRENGTH
Damage2: ''
Description: The Pokemon disappears into a dark dimension to infiltrate even the most
  impenetrable defenses. It may reappear during its next action.
DmgType: PHYSICAL
Effect: Charge Move. While charging this Move, other Moves will not affect the user.
  If the Target made a Shielding Action the shield is destroyed and won't have any
  effect.
Name: Phantom Force
Power: 3
Target: Foe
Type: Ghost
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