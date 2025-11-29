---
Accuracy1: Special
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Flinch
Attributes:
  DoubleAction: true
  FistMove: true
  Unique: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user hardens its limbs and then rotates them at great speed to hit
  the foe twice in a row. The blow can leave the victim crushed on the floor.
Effect: Single Target. Fist Move. Unique. Double Action. Roll 3 Chance Dice to Flinch
  the Foe after each hit. This Move may only Flinch once.
Name: Double Iron Bash
Power: 2
Target: Foe
Type: Steel
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