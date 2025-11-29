---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Burn
Attributes:
  AccuracyReduction: -1
  Charge: true
  Lethal: true
  Unique: true
Category: Special
Damage1: Special
Damage2: ''
Description: The user appears to become a block of ice, then it releases themselves
  from the ice with a devastating explosion. The exploding ice shards and fire blow
  all over the battlefield.
Effect: Single Target. Low Accuracy 1. Lethal. Charge Move. Unique. Roll 3 Chance
  Dice to Inflict 1st Degree Burn on the Target.
Name: Ice Burn
Power: 6
Target: Foe
Type: Ice
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