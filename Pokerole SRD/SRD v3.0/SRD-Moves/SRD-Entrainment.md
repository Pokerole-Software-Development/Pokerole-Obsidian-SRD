---
Accuracy1: Cool/Clever
Accuracy2: Athletic
AddedEffects: {}
Attributes:
  AbilityChange: true
  Duration: wholeScene
  Unique: true
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon trains and teaches their best ability to their target.\
  \ The target becomes a master of this ability in a record time."
Effect: Single Target. Replace the Target's Ability with the User's. Unique Abilities
  can't be passed or replaced. Whole Scene Duration. This effect does not end by switching
  out the affected Pokemon.
Name: Entrainment
Power: 0
Target: Foe
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