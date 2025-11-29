---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  AccuracyReduction: -1
  TripleAction: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The good ol\u2019 one-two with an even better twist! They never see\
  \ that last hit coming."
Effect: Single Target. Low Accuracy 1. Triple Action. *Add 1 Extra Die to the Damage
  Pool of the third hit.
Name: Triple Kick
Power: 1
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