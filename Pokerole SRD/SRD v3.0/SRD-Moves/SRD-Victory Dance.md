---
Accuracy1: Cool
Accuracy2: Perform
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: 1
    Stats:
    - Strength
    - Def
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "The user dances spelling the letters \u201CEZ\u201D in a display of\
  \ overconfidence. Encouraging their foes to either get good or give up already"
Effect: Target Self. Increase by 1 the User's Strength and Defense. Add 1 Die to the
  User's Damage Pool for all Non-Ranged Physical Attacks.
Name: Victory Dance
Power: 0
Target: Self
Type: Fighting
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