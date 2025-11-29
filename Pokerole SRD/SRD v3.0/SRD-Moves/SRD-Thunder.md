---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Paralyze
Attributes:
  AccuracyReduction: -2
  Lethal: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon commands the skies to send a giant lightning bolt to\
  \ a specific point. Difficult to command under clear skies, lethal during a storm.\
  \ Flying Pok\xE9mon are specially vulnerable."
Effect: Single Target. Low Accuracy 2. Lethal. Roll 3 Chance Dice to Paralyze the
  Target. Rain Weather eliminates Low Accuracy. Sunny Weather increases it to Low
  Accuracy 4. If the Target is Out of Range due to using "Fly", "Bounce", or "Sky
  Drop" this Move hits anyways.
Name: Thunder
Power: 5
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