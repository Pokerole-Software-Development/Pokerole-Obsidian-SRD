---
Accuracy1: Special/Strength
Accuracy2: Channel/Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 2
    Type: Poison
Attributes: {}
Category: Special
Damage1: Special/Strength
Damage2: ''
Description: "The Pok\xE9mon shoots slime ammunition from their cannon-like arm, or\
  \ strike the foe directly with the cannon arm. They may find themselves out of ammo,\
  \ but never out of options."
Effect: Single Target. Roll 2 Chance Dice to Poison the Target. *If the User's Strength
  score is higher than their Special, this Move becomes Physical, using Brawl for
  accuracy and inflicting damage with Strength.
Name: Shell Side Arm
Power: 3
Target: Foe
Type: Poison
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