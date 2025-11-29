---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Recoil: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon has had a terrible day and has a headache to match. Try\
  \ not to disturb the peace because their head really feels like exploding."
Effect: Area Move. Recoil.
Name: Mind Blown
Power: 6
Target: Area
Type: Fire
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