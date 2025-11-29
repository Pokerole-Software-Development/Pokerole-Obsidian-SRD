---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 2
    Type: Burn2
Attributes:
  AccuracyReduction: -1
  HighCritical: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "Setting their legs ablaze, the Pok\xE9mon throws a mighty kick that\
  \ sears the sides of the foe."
Effect: Single Target. Low Accuracy 1. High Critical. Roll 2 Chance Dice to inflict
  2nd Degree Burn on the Target.
Name: Blaze Kick
Power: 3
Target: Foe
Type: Fire
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