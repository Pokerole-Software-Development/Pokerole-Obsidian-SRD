---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  FixedDamage:
    Target: Targets
    Type: OneHitKO
Attributes:
  AccuracyReduction: -5
  Lethal: true
  Ranged: true
Category: Special
Damage1: '-'
Damage2: ''
Description: "The Pok\xE9mon reaches an absolute zero by being freezed from the inside\
  \ out. Urgent medical attention is required."
Effect: Single Target. Low Accuracy 5. Ranged. Deal Damage to the Target equal to
  its Remaining HP, plus 1 Lethal Damage.
Name: Sheer Cold
Power: 0
Target: Foe
Type: Ice
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