---
Accuracy1: Clever
Accuracy2: Nature/Intimidate
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: WorrySeed
Attributes:
  AbilityChange: true
  Duration: wholeScene
Category: Support
Damage1: ''
Damage2: ''
Description: "The user plants the seed of doubt and uncertainty on its foe. The foe\
  \ becomes such a worrywart that they can\u2019t even sleep at night."
Effect: Single Target. Replace the Target's Ability with "Insomnia". Whole Scene Duration.
  This effect does not end by switching out the affected Pokemon.
Name: Worry Seed
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