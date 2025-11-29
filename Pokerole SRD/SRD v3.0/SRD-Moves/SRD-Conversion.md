---
Accuracy1: Will
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: User
    Type: Conversion
Attributes:
  Duration: wholeScene
  Unique: true
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon downloads data from their database to add into their\
  \ own code."
Effect: Target Self. Unique. Change the User's Main Type at random. Whole Scene Duration.
Name: Conversion
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