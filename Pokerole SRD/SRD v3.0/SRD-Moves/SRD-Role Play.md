---
Accuracy1: Clever
Accuracy2: Perform
AddedEffects:
  Ailments:
  - Affects: User
    Type: ChangedAbility
Attributes:
  AbilityChange: true
  Duration: wholeScene
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon is a great actor. Their impersonations are really good!\
  \ ...maybe a bit too good."
Effect: Single Target. Replace the User's Ability with the Target's. Whole Scene Duration.
  Unique Abilities can't be copied.
Name: Role Play
Power: 0
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