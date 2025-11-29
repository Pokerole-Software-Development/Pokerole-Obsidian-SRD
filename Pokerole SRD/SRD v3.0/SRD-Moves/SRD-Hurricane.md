---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Confuse
Attributes:
  AccuracyReduction: -2
  Lethal: true
  WindMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon calls upon fierce gale winds. It\u2019ll be difficult\
  \ to summon the tempest on a clear day, but a little rain will enhance it into a\
  \ typhoon. Other pok\xE9mon in the air are in most danger."
Effect: Single Target. Low Accuracy 2. Lethal. Wind Move. Roll 3 Chance Dice to Confuse
  the Target. Rain Weather eliminates Low Accuracy. Sunny Weather increases to Low
  Accuracy 4. If the Target is Out of Range due to using "Fly", "Bounce" or "Sky Drop",
  this Move hits anyways.
Name: Hurricane
Power: 5
Target: Foe
Type: Flying
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