---
Accuracy1: Dexterity
Accuracy2: Stealth
AddedEffects: {}
Attributes:
  SwitcherMove: User
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon sheds their tail and leaves it as a decoy while it retreats\
  \ to safety and lets someone else deal with the threat."
Effect: Target Self. Switcher Move for the User. Deal 2 Damage to the User. Put a
  Substitute Decoy with 2 HP and the same defenses as the user. See p. 531
Name: Shed Tail
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