---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: FocusEnergy
Attributes:
  Duration: wholeScene
  HighCritical: true
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon concentrates all their focus on the battle to make their\
  \ attacks much more precise."
Effect: Target Self. All of the user's Physical & Special Moves now have "High Critical".
  Whole Scene Duration.
Name: Focus Energy
Power: 0
Target: Self
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