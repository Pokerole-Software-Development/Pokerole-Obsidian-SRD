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
Damage1: Strength
Damage2: ''
Description: The Pokemon uses its body to bind the foe, restraining and squeezing
  it.
DmgType: Physical
Effect: Block. Deal 2 dice of damage at the end of each Round. Lasts 4 Rounds. -2
  Accuracy.
Name: Bind
Power: 1
Target: Foe
Type: Normal
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