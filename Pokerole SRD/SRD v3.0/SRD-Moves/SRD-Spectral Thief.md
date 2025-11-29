---
Accuracy1: Dexterity
Accuracy2: Stealth
AddedEffects: {}
Attributes:
  Unique: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: Through the shadows, the user sneaks on its target to steal its life
  force and consume it, leaving the victim with a sense of grief and loss.
Effect: Single Target. Unique. Before the User deals damage with this Move, steal
  all Attribute Increases the Target may have. Reduced Attributes on the Target remain.
Name: Spectral Thief
Power: 3
Target: Foe
Type: Ghost
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