---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: PayDay
  StatChanges:
  - Affects: User
    Stages: -2
    Stats:
    - Special
Attributes:
  PhysicalRanged: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon calls a rain of gold to fall from the sky. All the greedy\
  \ Pok\xE9mon who threw themselves at the money get in range for an explosion of\
  \ golden light. Worth it!"
Effect: 'Area Move. Reduce the User''s Special by 2. At the end of the battle give
  the User and every Trainer whose Pokemon was hit, Money equal to their Rank: Starter/Rookie
  - 100 Standard - 250 Advanced - 500 Ace or more - 1000'
Name: Make It Rain
Power: 5
Target: Area
Type: Steel
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