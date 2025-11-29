---
Accuracy1: Tough
Accuracy2: Perform
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: 1
    Stats:
    - Strength
    - Dexterity
    - Special
    - Def
    - SpDef
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon shakes its scales around, to sharpen, shed, and rearrange\
  \ them. It\u2019s a bit rough, but in the end the Pok\xE9mon feels more focused\
  \ for battle."
Effect: Target Self. User deals Damage Dice to itself equal to Half of its Total HP
  rounded down. Increase by 1 the User's Strength, Dexterity, Special, Defense and
  Sp. Defense.
Name: Clangorous Soul
Power: 0
Target: Self
Type: Dragon
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