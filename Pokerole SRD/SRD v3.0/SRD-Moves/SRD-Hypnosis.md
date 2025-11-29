---
Accuracy1: Clever
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Sleep
Attributes:
  AccuracyReduction: -3
Category: Support
Damage1: ''
Damage2: ''
Description: By staring at an hypnotic pendulum, the target is suggestioned to feel
  tired and close its eyelids.
Effect: Single Target. Low Accuracy 3. Put the Target to sleep. Dark-Type Pokemon
  are affected by this Move.
Name: Hypnosis
Power: 0
Target: Foe
Type: Psychic
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