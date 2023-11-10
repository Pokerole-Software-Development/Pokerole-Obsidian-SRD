---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 2
    Type: Flinch
  - Affects: Targets
    ChanceDice: 2
    Type: Paralyze
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user lands an electrified bite on the foe. The direct current may
  affect the foe greatly.
Effect: Roll 2 Chance Dice to Flinch the foe. Roll 2 Chance Dice to Paralyze the foe.
Name: Thunder Fang
Power: 2
Target: Foe
Type: Electric
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