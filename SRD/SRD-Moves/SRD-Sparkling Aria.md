---
Accuracy1: SPECIAL
Accuracy2: PERFORM
Damage1: SPECIAL
Damage2: ''
Description: The Pokemon sings a beautiful melody, the song comes out as a sparkling
  fountain, bursting upon impact and quenching any fire in its path.
DmgType: SPECIAL
Effect: Sound Based. Area Attack. If an affected Pokemon had any of the Burn Status
  Conditions, heal it instead of dealing damage.
Name: Sparkling Aria
Power: 3
Target: Area
Type: Water
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