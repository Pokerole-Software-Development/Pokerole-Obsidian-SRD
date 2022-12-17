---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Paralyze
Attributes:
  AccuracyReduction: 1
  Charge: true
  Lethal: true
  PhysicalRanged: true
Damage1: Strength
Damage2: ''
Description: The user appears to become a block of ice, then it releases itself from
  the ice with a devastating discharge. The exploding ice shards and the lightning
  fly all over the battlefield.
DmgType: Physical
Effect: Lethal. Ranged. Charge Move. Roll 3 Chance Dice to Paralyze the Foe. -1 Accuracy.
Name: Freeze Shock
Power: 6
Target: Foe
Type: Ice
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`