---
Accuracy1: Strength/Special
Accuracy2: Channel
AddedEffects: {}
Attributes: {}
Category: Dual
Damage1: Strength/Special
Damage2: ''
Description: "A blast of sharp crystals and Tera energy, if the Pok\xE9mon is Terastallized\
  \ the energy\u2019s type will change. It is something beautiful to witness."
Effect: Single Target. *If the User is actively Terastallized, the Type of this Move
  changes to match that of the Tera-Type. This affects Weaknesses, Resistances and
  STAB accordingly.
Name: Tera Blast
Power: 3
Target: Foe
Type: Normal
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