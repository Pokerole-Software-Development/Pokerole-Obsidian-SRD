---
Accuracy1: Strength
Accuracy2: Athletic/Brawl
AddedEffects: {}
Attributes:
  BlockDamagePool: 0
Category: Support
Damage1: ''
Damage2: ''
Description: "Force the target into a wrestling lock; use a lasso rodeo-style; or\
  \ simply cling onto one of their legs \u2014 the point is: you won\u2019t let them\
  \ escape!"
Effect: Single Target. Blocks. The Target may resist this Maneuver by rolling Strength
  or Dexterity and scoring the same or more Successes than the User. The User can't
  Act while Grappling. The User can release the Grapple at any point to act.
Name: Grapple
Power: 0
Target: Foe
Type: Typeless
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