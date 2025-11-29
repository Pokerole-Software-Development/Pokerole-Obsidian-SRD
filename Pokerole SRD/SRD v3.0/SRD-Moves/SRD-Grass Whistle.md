---
Accuracy1: Beauty
Accuracy2: Perform
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Sleep
Attributes:
  AccuracyReduction: -3
  SoundMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: A soothing and relaxing melody created with the sounds of nature. It
  is a very subtle tone, so it may be hard to listen.
Effect: Single Target. Low Accuracy 3. Sound Move. Put the Target to Sleep.
Name: Grass Whistle
Power: 0
Target: Foe
Type: Grass
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