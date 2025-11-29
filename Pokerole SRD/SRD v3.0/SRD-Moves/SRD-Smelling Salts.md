---
Accuracy1: Insight
Accuracy2: Brawl
AddedEffects: {}
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon uses strong smelling salts to purify the arena or to\
  \ throw into the foe\u2019s face. Any paralized Pok\xE9mon gets a sudden jolt at\
  \ the powerfull smell."
Effect: Single Target. *If the Target is Paralyzed, add 2 Extra Dice to the Damage
  pool of this Move. After dealing damage, cure the Target's Paralysis
Name: Smelling Salts
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