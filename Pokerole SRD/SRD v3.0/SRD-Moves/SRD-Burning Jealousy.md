---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Burn
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: "The user can\u2019t stand the idea that others are better than them.\
  \ Their jealousy manifests in the form of a fiery aura that sticks to those the\
  \ user despises de most."
Effect: Target All Foes in Range. *Inflict 1st Degree Burn on all affected Targets
  with Increased Attributes.
Name: Burning Jealousy
Power: 3
Target: All Foes
Type: Fire
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