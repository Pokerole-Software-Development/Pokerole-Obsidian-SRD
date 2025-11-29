---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 2
    Type: Paralyze
  - Affects: Targets
    ChanceDice: 2
    Type: Burn
  - Affects: Targets
    ChanceDice: 2
    Type: Freeze
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: The foe has three problems and this Move is all of them.
Effect: Single Target. Roll 2 Chance Dice to inflict 1st Degree Burn on the Target.
  Roll 2 Chance Dice to Freeze the Target. Roll 2 Chance Dice to Paralyze the Target.
Name: Tri Attack
Power: 3
Target: Foe
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