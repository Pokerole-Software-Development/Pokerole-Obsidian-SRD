---
Accuracy1: Strength
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Lethal: true
  Unique: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon strikes with a devastating electric impact, said impact\
  \ will grow larger and stronger if there\u2019s a special kind of fire nearby."
Effect: Single Target. Lethal. Unique. *If the Move "Fusion Flare" has already been
  used by anyone this Round, add 4 Extra Dice to the Damage Pool of this Move.
Name: Fusion Bolt
Power: 4
Target: Foe
Type: Electric
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