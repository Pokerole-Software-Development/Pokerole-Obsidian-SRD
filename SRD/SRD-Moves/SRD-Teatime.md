---
Accuracy1: Insight
Accuracy2: Etiquette
AddedEffects: {}
Attributes: {}
Damage1: ''
Damage2: ''
Description: The Pokemon gathers everyone for a cup of delicious tea. Not eating a
  snack along with it would be a waste.
DmgType: Support
Effect: Those affected eat their held berries without gaining their effects. Outside
  of battle will diffuse violent intentions for a few minutes
Name: Teatime
Power: 0
Target: Area
Type: Normal
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`