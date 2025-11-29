---
Accuracy1: Insight
Accuracy2: Empathy
AddedEffects: {}
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon gathers the souls the departed and helps them fulfill\
  \ their desire of revenge before moving on."
Effect: Single Target. *Add 2 Extra Dice to the Damage pool of this Move for every
  ally that Fainted during this Battle Up to 8 Dice may be added this way.
Name: Last Respects
Power: 2
Target: Foe
Type: Ghost
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