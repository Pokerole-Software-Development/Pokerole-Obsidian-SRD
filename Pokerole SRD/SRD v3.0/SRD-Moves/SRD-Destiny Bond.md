---
Accuracy1: Will
Accuracy2: Stealth
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: DestinyBond
Attributes:
  UserFaints: true
Category: Support
Damage1: ''
Damage2: ''
Description: "Through a mystical bond, everyone who brings disgrace to this Pok\xE9\
  mon will suffer the exact same fate."
Effect: Target Self. If the user faints this Round due to damage frm a Physical or
  Special Move, the Pokemon who dealt the damage is dealt damage equal to their remaining
  Hp. This Move will fail if it was used the previous Round.
Name: Destiny Bond
Power: 0
Target: Self
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