---
Accuracy1: Clever
Accuracy2: Stealth
AddedEffects: {}
Attributes:
  AbilityChange: true
  Duration: wholeScene
  Unique: true
Category: Support
Damage1: ''
Damage2: ''
Description: "By doodling a quick drawing of their target the doodle somehow allows\
  \ the Pok\xE9mon to make use of the depicted creature\u2019s powers."
Effect: Single Target. Replace the User's Ability with the Target's. Whole Scene Duration.
  Unique Abilities can't be copied.
Name: Doodle
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