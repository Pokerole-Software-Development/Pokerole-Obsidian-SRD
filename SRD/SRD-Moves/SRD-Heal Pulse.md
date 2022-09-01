---
Accuracy1: WILL
Accuracy2: CHANNEL
Damage1: ''
Damage2: ''
Description: The user emits a pulse of energy that heals the wounds of its allies.
DmgType: SUPPORT
Effect: Basic Heal. If successful spend 1 Will to activate.
Name: Heal Pulse
Power: 0
Target: One Ally
Type: Psychic
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