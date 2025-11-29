---
Accuracy1: Strength/Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Unique: true
Category: Dual
Damage1: Strength/Special
Damage2: ''
Description: "Tera crystals full of energy fall from the sky as meteors. A beautiful\
  \ but extemely chaotic scene follows as all Pok\xE9mon absorb the Tera Energy without\
  \ control."
Effect: Target All Foes in Range. Unique Move. *If the User is actively Terastallized,
  the Type of this Move changes to match that of the Tera-Type, this affects Weaknesses,
  Resistances and STAB accordingly. Change the type of those affected at random.
Name: Tera Starstorm
Power: 5
Target: All Foes
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