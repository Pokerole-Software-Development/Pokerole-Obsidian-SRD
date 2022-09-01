---
Accuracy1: DEXTERITY
Accuracy2: BRAWL
Damage1: STRENGTH
Damage2: ''
Description: The Pokemon happily runs into a wheel made of electricity that strikes
  the foe. If the user is feeling hungry the wheel's energy is replaced by a dark
  aura.
DmgType: PHYSICAL
Effect: "If successful, Increase user's Dexterity. If the user is in \u201CHangry\u201D\
  \ Form this Move is considered to be Dark-Type."
Name: Aura Wheel
Power: 4
Target: Foe
Type: Electric
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