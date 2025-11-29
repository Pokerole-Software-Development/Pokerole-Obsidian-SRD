---
Accuracy1: Clever
Accuracy2: Stealth
AddedEffects: {}
Attributes:
  Reaction: '6'
  ShieldMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: The user takes notice of the good stuff on the other side and quickly
  takes it for themselves. Finders keepers, losers weepers!
Effect: Single Target. Reaction 6. Remove any Increase/Reduction on the Foe's Attributes,
  Active Shield Moves, Healing effects on the Foe, or effects on its side of the field;
  and place them on the User instead. See p. 531 for more info.
Name: Snatch
Power: 0
Target: Foe
Type: Dark
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