---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Block
Attributes:
  AccuracyReduction: 1
  BlockDamagePool: 2
Category: Physical
Damage1: Strength
Damage2: ''
Description: The Pokemon traps its foe with its body or vines, causing some damage.
Effect: Blocks. Roll 2 Dice of Damage against the foe at the end of each Round. Lasts
  4 Rounds. -1 Accuracy.
Name: Wrap
Power: 1
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