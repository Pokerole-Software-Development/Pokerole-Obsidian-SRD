---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  StatChanges:
  - Affects: Targets
    ChanceDice: 5
    Stages: -2
    Stats:
    - Def
Attributes:
  Lethal: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user crushes its claws against the foe, it may pierce the skin of
  the foe.
Effect: Roll 5 Chance Dice to Reduce the target's Defense by 2. Lethal.
Name: Crush Claw
Power: 3
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