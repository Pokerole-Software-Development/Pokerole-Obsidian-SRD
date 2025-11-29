---
Accuracy1: Vitality
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -1
    Stats:
    - SpDef
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon produces a sap from the tart apples they feed on, if\
  \ the apples are not ripe their sap will be acidic and bad for teeth."
Effect: Single Target. Reduce the Foe's Sp. Defense by 1.
Name: Apple Acid
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