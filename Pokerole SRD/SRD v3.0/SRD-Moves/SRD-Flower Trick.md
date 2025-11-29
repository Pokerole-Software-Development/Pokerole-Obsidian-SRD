---
Accuracy1: Dexterity
Accuracy2: Stealth
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -1
    Stats:
    - Dexterity
Attributes:
  AlwaysCrit: true
  NeverMiss: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user throws a bouquet of flowers at the target, who holds them close
  believing them to be a gift, only to realize the bouquet were flower bombs.
Effect: Single Target. Never Miss. This Move is always considered to be a Critical
  Hit and gets the proper Bonus for it.
Name: Flower Trick
Power: 2
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