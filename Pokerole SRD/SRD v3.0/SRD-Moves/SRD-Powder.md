---
Accuracy1: Insight
Accuracy2: Nature
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Powder
Attributes:
  PowderMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: The foe gets covered by a very flammable powder, the smallest source
  of fire will ignite it with explosive results.
Effect: Single Target. Powder Move. The next time the Target uses a Fire-Type Move,
  Roll Typeless Damage Dice equal to that Move's power, ignore defenses.
Name: Powder
Power: 0
Target: Foe
Type: Bug
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