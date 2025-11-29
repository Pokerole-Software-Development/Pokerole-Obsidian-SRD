---
Accuracy1: Strength
Accuracy2: Channel
AddedEffects:
  FixedDamage:
    Target: Targets
    Type: OneHitKO
Attributes:
  AccuracyReduction: -5
  Lethal: true
  PhysicalRanged: true
  Ranged: true
Category: Physical
Damage1: '-'
Damage2: ''
Description: "The earth rips apart underneath the target and swallows them whole.\
  \ You\u2019ll need a rescue team to recover the unlucky victim from the deep."
Effect: Single Target. Low Accuracy 5. Ranged. Deal Damage to the Target equal to
  its Remaining HP, plus 1 Lethal Damge. If the Target is out of range due to using
  the Move "Dig" this Move hits anyways.
Name: Fissure
Power: 0
Target: Foe
Type: Ground
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