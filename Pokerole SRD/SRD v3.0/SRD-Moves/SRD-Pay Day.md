---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: PayDay
Attributes:
  PhysicalRanged: true
  Ranged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "This Pok\xE9mon brings good fortune to businesses and trainers alike.\
  \ Make sure to use some of that hard earned money to buy them a treat."
Effect: 'Single Target. Ranged. At the end of the battle give Money to your Trainer
  Equal to their Rank: Starter/Rookie - 100 Standard - 250 Advanced - 500 Ace or more
  - 1000'
Name: Pay Day
Power: 2
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