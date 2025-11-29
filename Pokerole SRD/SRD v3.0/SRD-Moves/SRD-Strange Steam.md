---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 2
    Type: Confuse
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: The user releases an addictive and sweet-smelling steam. Do not be fooled
  as it is mildly toxic with nasty side-effects.
Effect: Single Target. Roll 2 Chance Dice to Confuse the Target.
Name: Strange Steam
Power: 3
Target: Foe
Type: Fairy
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