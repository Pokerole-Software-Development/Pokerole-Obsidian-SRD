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
Attributes: {}
Damage1: Special
Damage2: ''
Description: The user sends out a subterranean wave that bursts on the ground bellow
  the target. It looks like the earth molds to the Pokemon's will.
DmgType: Special
Effect: Roll 1 Chance Dice to Reduce the foe's Sp. Defense.
Name: Earth Power
Power: 3
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