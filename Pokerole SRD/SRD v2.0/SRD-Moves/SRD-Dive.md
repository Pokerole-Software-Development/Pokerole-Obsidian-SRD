---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Target
    Rounds: 1
    Type: Diving
Attributes:
  Charge: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user submerges into the water and continues diving at an insane speed.
Effect: Charge Move. While charging this move, the User will be out of range. Allows
  the Pokemon to swim into Deep Waters.
Name: Dive
Power: 2
Target: Foe
Type: Water
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