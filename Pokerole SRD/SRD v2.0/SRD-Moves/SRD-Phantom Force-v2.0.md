---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  Charge: true
  DestroyShield: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The Pokemon disappears into a dark dimension to infiltrate even the most
  impenetrable defenses. It may reappear during its next action.
Effect: Charge Move. While charging this Move, other Moves will not affect the user.
  If the Target made a Shielding Action the shield is destroyed and won't have any
  effect.
Name: Phantom Force
Power: 3
Target: Foe
Type: Ghost
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