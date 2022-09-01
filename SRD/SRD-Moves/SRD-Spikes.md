---
Accuracy1: SPECIAL
Accuracy2: NATURE
Damage1: ''
Damage2: ''
Description: The Pokemon shoots pointy pebbles or thorns around the field that deal
  damage to anyone coming from that side.
DmgType: SUPPORT
Effect: Foe Pokemon that enter the battlefield will lose 1 HP, this effect does not
  stack. Pokemon with the Levitate ability and Flying Type Pokemon are immune to this
  effect. Entry Hazard.
Name: Spikes
Power: 0
Target: Battlefield
Type: Ground
---

#PokeroleSRD/Moves

## `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`