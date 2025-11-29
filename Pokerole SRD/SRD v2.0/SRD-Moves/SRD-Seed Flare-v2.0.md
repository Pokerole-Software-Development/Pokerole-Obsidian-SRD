---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Targets
    ChanceDice: 4
    Stages: -2
    Stats:
    - SpDef
Attributes:
  Lethal: true
Category: Special
Damage1: Special
Damage2: ''
Description: Shaymin releases an explosion of pollen and seeds that the foe cannot
  shake off, leaving it vulnerable. Over time, these seeds will grow into gigantic
  trees of life.
Effect: Lethal. Roll 4 Chance Dice to Reduce the foe's Sp. Defense by 2.
Name: Seed Flare
Power: 5
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