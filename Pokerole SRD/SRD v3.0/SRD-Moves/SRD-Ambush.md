---
Accuracy1: Dexterity
Accuracy2: Stealth
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: Sneak through the shadows, stay low to the ground, and prepare yourself
  to pounce on an unsuspecting foe.
Effect: 'Single Target. Before the Battle starts, Target may resist by rolling: Insight
  + Alert and scoring the same or more Successes. The User has 1 Action before Initiatives
  are rolled in which the Target can''t act. Other foes can still Evade or Clash during
  this time.'
Name: Ambush
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