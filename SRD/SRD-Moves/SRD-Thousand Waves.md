---
Accuracy1: SPECIAL
Accuracy2: BRAWL
Damage1: STRENGTH
Damage2: ''
Description: Solid ground becomes a sandtrap, cracked earth will close to ensnare
  your feet. It's as it the land itself wanted to trap you. There is no attacker nor
  escape in sight.
DmgType: PHYSICAL
Effect: Blocks. Ranged. All Foes in Range.
Name: Thousand Waves
Power: 3
Target: All Foes
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