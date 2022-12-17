---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Block
Attributes:
  AccuracyReduction: 2
  BlockDamagePool: 2
Damage1: Special
Damage2: ''
Description: Trap the foe inside a violent swirling whirlpool that makes the foe unable
  to escape the battle.
DmgType: Special
Effect: Block. Deal 2 dice of damage at the end of each Round. Lasts 4 Rounds. -2
  Accuracy.
Name: Whirlpool
Power: 2
Target: Foe
Type: Water
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