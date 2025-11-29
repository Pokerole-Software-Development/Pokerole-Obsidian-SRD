---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects: {}
Attributes:
  IgnoreDefenses: true
  IgnoreShield: true
  NeverMiss: true
  Unique: true
Category: Special
Damage1: Special
Damage2: ''
Description: The laws of physics forbid one object from being in many places at once
  and from occupying the same space as other bodies. But the user disregards their
  autorithy.
Effect: Single Target. Never Miss. Unique. Ignore Defenses. Ignore Shield Moves and
  Force Field.
Name: Hyperspace Hole
Power: 3
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