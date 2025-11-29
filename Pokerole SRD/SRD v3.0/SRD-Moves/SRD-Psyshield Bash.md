---
Accuracy1: Vitality
Accuracy2: Brawl
AddedEffects:
  StatChanges:
  - Affects: User
    ChanceDice: 3
    Stages: 1
    Stats:
    - Def
    - SpDef
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user cloaks itself in a shield of psychic energy then rams into the
  foe.
Effect: Single Target. Roll 3 Chance Dice to Increase by 1 the User's Defense and
  Sp. Defense.
Name: Psyshield Bash
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