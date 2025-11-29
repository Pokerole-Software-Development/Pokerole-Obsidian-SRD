---
Accuracy1: Will
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: User
    Type: Conversion2
Attributes:
  Duration: wholeScene
  Unique: true
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon downloads data from a Move that was used against it and\
  \ changes their code to resist future attacks."
Effect: Target Self. Unique. After being dealt damage by a Physical or Special Move,
  change the User's Main Type to a Type resistant to that Move. Whole Scene Duration.
Name: Conversion 2
Power: 0
Target: Self
Type: Normal
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