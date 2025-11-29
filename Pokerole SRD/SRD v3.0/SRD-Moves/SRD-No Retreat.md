---
Accuracy1: Vitality
Accuracy2: Alert
AddedEffects:
  Ailments:
  - Affects: User
    Type: Block
  StatChanges:
  - Affects: User
    Stages: 1
    Stats:
    - Strength
    - Dexterity
    - Special
    - Def
    - SpDef
Attributes:
  Duration: wholeScene
Category: Support
Damage1: ''
Damage2: ''
Description: No surrender. No retreat. Until victory, always!
Effect: Target Self. Increase by 1 the User's Strength, Dexterity, Special, Defense
  and Sp. Defense. Blocks. Whole Scene Duration.
Name: No Retreat
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