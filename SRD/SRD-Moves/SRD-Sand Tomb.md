---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Block
Attributes:
  AccuracyReduction: 2
  BlockDamagePool: 2
  PhysicalRanged: true
Damage1: Strength
Damage2: ''
Description: The Pokemon creates a shifting sand pit around the foe, leaving it unable
  to escape.
DmgType: Physical
Effect: Ranged. Block. Roll 2 Dice of Damage against the foe at the end of every Round.
  Lasts 4 Rounds. -2 Accuracy.
Name: Sand Tomb
Power: 2
Target: Foe
Type: Ground
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