---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: Zygarde shoots a beam that fractures the target to its core, rendering
  it unable to sustain even the most basic of its traits.
Effect: If successful and the target of this Move has already inflicted damage this
  Round, remove the Foe's Ability for the rest of the Scene. (Battle Bond, Comatose,
  Disguise, Multitype, Power Construct, RKS System, Schooling, Stance Change & Shields
  Down are exceptions)
Name: Core Enforcer
Power: 4
Target: Foe
Type: Dragon
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