---
Accuracy1: Will
Accuracy2: Intimidate
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -2
    Stats:
    - Strength
    - Dexterity
    - Special
    - Def
    - SpDef
Attributes:
  Duration: wholeScene
  UserFaints: true
Category: Support
Damage1: ''
Damage2: ''
Description: "As they take their last breath, the Pok\xE9mon leaves behind an imprint\
  \ of regret on their foe."
Effect: Single Target. The User faints. Reduce by 2 the foe's Strength, Dexterity,
  Special, Defense, and Sp. Defense. Whole Scene Duration. This effect does not end
  by switching out the affected Pokemon.
Name: Memento
Power: 0
Target: Foe
Type: Dark
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