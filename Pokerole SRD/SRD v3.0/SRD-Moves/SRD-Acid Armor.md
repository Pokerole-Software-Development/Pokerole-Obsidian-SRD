---
Accuracy1: Vitality
Accuracy2: Nature
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: 2
    Stats:
    - Def
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "Highly acidic goop oozes through the pores of this Pok\xE9mon. Touching\
  \ it immediately causes a burning pain. Preventing foes from getting too close."
Effect: Target Self. Increase the User's Defense by 2.
Name: Acid Armor
Power: 0
Target: Self
Type: Poison
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