---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 2
    Type: Flinch
  - Affects: Targets
    ChanceDice: 2
    Type: Freeze
Attributes:
  AccuracyReduction: 1
Damage1: Strength
Damage2: ''
Description: The user bites the foe and releases a gelid breath through its mouth.
DmgType: Physical
Effect: Roll 2 Chance Dice to Flinch the foe. Roll 2 Chance Dice to Freeze the foe.
  -1 Accuracy.
Name: Ice Fang
Power: 2
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