---
Accuracy1: Insight
Accuracy2: Alert
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: MiracleEye
Attributes:
  Duration: wholeScene
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon opens up the third eye. Their sight trascends the barriers\
  \ of flesh. No one goes undetected."
Effect: Target Self. The User's Psychic-Type Moves ignore Dark-Type Immunity. Target
  cannot Evade the User's Moves. This Pokemon's Accuracy cannot be Reduced by Move's,
  Items or Abilities (ie Sand Attack, Bright Powder, etc.). Whole Scene Duration
Name: Miracle Eye
Power: 0
Target: Self
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