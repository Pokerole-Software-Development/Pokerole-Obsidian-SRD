---
Accuracy1: Cute/Beauty
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
Description: "The Pok\xE9mon sings a lullaby; the sound is so comforting that it evokes\
  \ memories of being tucked in bed and kissed good night."
Effect: Single Target. Low Accuracy 3. Sound Move. Put the Target to sleep.
Name: Sing
Power: 0
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