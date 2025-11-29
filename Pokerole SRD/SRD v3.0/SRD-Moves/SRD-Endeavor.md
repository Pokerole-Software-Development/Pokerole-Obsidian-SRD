---
Accuracy1: Will
Accuracy2: Channel
AddedEffects: {}
Attributes:
  IgnoreDefenses: true
Category: Physical
Damage1: Varies
Damage2: ''
Description: "Through sheer willpower the Pok\xE9mon manages to level the conditions\
  \ of the battle despite their own injuries."
Effect: Single Target. Roll Dice of Normal-Type Damage equal to the difference between
  the User's current HP and the Target's max HP. Ignore defenses. Up to 10 Dice may
  be rolled this way. This Damage cannot make the Target's HP go lower than the User's
  current HP.
Name: Endeavor
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