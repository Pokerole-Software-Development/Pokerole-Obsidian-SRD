---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Silence
Attributes:
  Duration: wholeScene
Category: Physical
Damage1: Strength
Damage2: ''
Description: "A heinous attack to a Pok\xE9mon\u2019s throat that will leave them\
  \ unable to make a sound for hours."
Effect: Single Target. The target cannot use any "Sound Based" Move. Whole Scene Duration.
  This effect does not end by switching out the affected Pokemon.
Name: Throat Chop
Power: 3
Target: Foe
Type: Dark
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