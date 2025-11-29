---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Confuse
Attributes:
  AccuracyReduction: -2
Category: Special
Damage1: Special
Damage2: ''
Description: "Through a series of reflective surfaces, the Pok\xE9mon redirects a\
  \ beam through unexpected directions. The foe is at a loss; they don\u2019t know\
  \ if what they see is real or a reflection."
Effect: Single Target. Low Accuracy 2. Roll 3 Chance Dice to Confuse the Target.
Name: Mirror Shot
Power: 2
Target: Foe
Type: Steel
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