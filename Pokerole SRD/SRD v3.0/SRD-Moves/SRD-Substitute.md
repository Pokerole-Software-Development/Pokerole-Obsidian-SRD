---
Accuracy1: Vitality
Accuracy2: Stealth
AddedEffects:
  FixedDamage:
    Target: User
    Type: Absolute
    Value: 2
Attributes:
  SwitcherMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon disappears in a poof of smoke. A decoy identical to the\
  \ user takes their place in battle. The user keeps attacking from the shadows while\
  \ the decoy serves as distraction."
Effect: Target Self. Deal 2 damage to the User. Put a Substitute Decoy with 2 HP and
  the same defenses as the user. See p. 531
Name: Substitute
Power: 0
Target: Self
Type: Normal
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