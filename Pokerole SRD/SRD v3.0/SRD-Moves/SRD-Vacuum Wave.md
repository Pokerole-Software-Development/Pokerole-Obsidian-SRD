---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Reaction: '1'
Category: Special
Damage1: Special
Damage2: ''
Description: "Using their chi as a vacuum, the Pok\xE9mon pulls the foe closer, the\
  \ foe gets hurt by the sudden force wave on its body"
Effect: Single Target. Reaction 1.
Name: Vacuum Wave
Power: 2
Target: Foe
Type: Fighting
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