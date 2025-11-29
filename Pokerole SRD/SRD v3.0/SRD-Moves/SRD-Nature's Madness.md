---
Accuracy1: Insight
Accuracy2: Nature
AddedEffects:
  FixedDamage:
    MaxValue: 10
    Target: Targets
    Type: HpPercentage
    Value: 0.5
Attributes:
  AccuracyReduction: -1
  IgnoreDefenses: true
Category: Special
Damage1: Varies
Damage2: ''
Description: The forces of nature attack as if they had a will of their own. Water
  will try to drown you, plants will trap you, lightning will come out of nowhere,
  even your own body will fail you.
Effect: Single Target. Low Accuracy 1. Damage Roll is Half of the Target's remaining
  HP (up to 10 Dice) Rounded down. If the remaining HP of the Target is 1, this move
  fails. Ignore Defenses.
Name: Nature's Madness
Power: 0
Target: Foe
Type: Fairy
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