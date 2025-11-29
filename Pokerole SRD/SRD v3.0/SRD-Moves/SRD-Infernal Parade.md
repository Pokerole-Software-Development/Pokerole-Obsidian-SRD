---
Accuracy1: Insight
Accuracy2: Intimidate
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 2
    Type: Burn2
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: "'You may not be the type to faint when things are odd or things are\
  \ quaint. But seeing flames you know that ain\u2019t will scorch you into dismay't\
  \ will scorch you into dismay.'"
Effect: Single Target. Roll 2 Chance Dice to inflict 2nd Degree Burn on the Foe. *If
  the Target has an active Status Condition, add 2 Extra Dice to the Damage Pool of
  this Move.
Name: Infernal Parade
Power: 2
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