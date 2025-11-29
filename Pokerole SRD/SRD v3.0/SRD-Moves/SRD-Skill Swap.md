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
  Unique: true
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon enters their foe\u2019s mind to assimilate the traits\
  \ of that species while make the foe think it is a member from another species.\
  \ The foe gets an identity crisis afterwards."
Effect: Single Target. Switch the User's Ability with the Target's. Whole Scene Duration.
  This affect does not end by switching out the affected Pokemon. Unique Abilities
  can't be switched.
Name: Skill Swap
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