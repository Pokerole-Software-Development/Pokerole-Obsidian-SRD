---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Targets
    ChanceDice: 5
    Stages: -1
    Stats:
    - SpDef
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: The user engulfs itself in a blinding light and shoots a beam at its
  foe. This light leaves the foe powerless to resist against anyone.
Effect: Roll 5 Chance Dice to Reduce the foe's Sp. Defense. This Effect can be repeated
  up to 3 times per Target.
Name: Luster Purge
Power: 2
Target: Foe
Type: Psychic
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