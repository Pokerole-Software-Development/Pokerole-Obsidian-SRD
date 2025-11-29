---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Targets
    ChanceDice: 1
    Stages: -1
    Stats:
    - SpDef
Attributes:
  ProjectileMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: "Gathering nature\u2019s energy from nearby plants, trees and roots,\
  \ the Pok\xE9mon forms a ball to shoot at the enemy. Sadly, the surrounding plants\
  \ will be dry afterwards."
Effect: Single Target. Projectile Move. Roll 1 Chance Die to Reduce the Target's Sp.
  Defense by 1.
Name: Energy Ball
Power: 3
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