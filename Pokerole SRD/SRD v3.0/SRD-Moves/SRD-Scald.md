---
Accuracy1: Dexterity/Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Burn
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: The user shoots boiling water at the foe, immediately causing blisters.
Effect: Single Target. Roll 3 Chance Dice to inflict 1st Degree Burn on the Target.
  If a Target is Out of Range due to using the Move "Dive", this Move hits anyways.
Name: Scald
Power: 3
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