---
Accuracy1: Special
Accuracy2: Nature
AddedEffects: {}
Attributes:
  AccuracyReduction: -1
  IgnoreDefenses: true
  PhysicalRanged: true
  Ranged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: From a magical bean, the user grows a cute stalk that will attach itself
  to the nearest target. Once it ingrains, it will grow and grow and grow until it
  reaches the sky.
Effect: Single Target. Low Accuarcy 1. Ranged. Spend 1 Will point to activate. At
  the end of the Round, Roll 2 Dice of Typeless Damage against one target. Ignore
  Defenses. The User deals 1 HP for every damage dealt this way. If the user of this
  Move is at its Final Stage of Evolution, this move fails.
Name: Sappy Seed
Power: 3
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