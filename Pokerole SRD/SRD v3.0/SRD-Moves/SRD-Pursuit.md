---
Accuracy1: Dexterity
Accuracy2: Athletic/Stealth
AddedEffects: {}
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon is relentless in its pursuit of their target, striking\
  \ it just as it believed it had escaped."
Effect: Single Target. *If a Target hit by this Move is recalled, attempts to Run
  Away, uses a Switcher Move or is the Target of a Switcher Move, Deal 2 Typeless
  Damage to it. Outside of battle, aid in catching a fleeing target.
Name: Pursuit
Power: 2
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