---
Accuracy1: Clever
Accuracy2: Nature
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Sleep
Attributes:
  AccuracyReduction: -3
  PowderMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon spouts a cloud of somniferous pollen to know out their\
  \ foe, the only problem is that the foe must inhale enough of the pollen for it\
  \ to take effect."
Effect: Single Target. Low Accuracy 3. Powder Move. Put the Target to Sleep.
Name: Sleep Powder
Power: 0
Target: Foe
Type: Grass
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