---
Accuracy1: Insight
Accuracy2: Brawl
AddedEffects: {}
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: "There\u2019s energy all around us, hidden secretly in the most incospicuous\
  \ places. This Move makes use of that energy bringing the secret to light."
Effect: Single Target. Roll 3 Chance Dice to Inflict Status determined by the environment
  or active Terrain. See more on p. 530
Name: Secret Power
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