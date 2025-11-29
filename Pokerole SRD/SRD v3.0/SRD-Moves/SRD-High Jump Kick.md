---
Accuracy1: Dexterity
Accuracy2: Athletic
AddedEffects: {}
Attributes:
  AccuracyReduction: -2
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The user launches itself up three stories high to pummel down with a\
  \ brutal kick. Let\u2019s just trust it\u2019s got a good aim from that distance."
Effect: Single Target. Low Accuracy 2. If the Accuracy roll fails, Roll 5 Dice of
  Typeless Damage against the user, ignoring defenses.
Name: High Jump Kick
Power: 5
Target: Foe
Type: Fighting
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