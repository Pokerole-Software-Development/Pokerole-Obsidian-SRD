---
Accuracy1: DEXTERITY
Accuracy2: CHANNEL
Damage1: SPECIAL
Damage2: ''
Description: A laser briefly beams away from the Pokemon, whatever it hits explodes
  a second later. This move can be modified with the right programming of a computer.
DmgType: SPECIAL
Effect: 'Lethal. If Genesect is performing this Move, this Move''s type may change
  to: Fire, Ice, Water, or Electric depending on the Driver it has as Held Item.'
Name: Techno Blast
Power: 5
Target: Foe
Type: Normal
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