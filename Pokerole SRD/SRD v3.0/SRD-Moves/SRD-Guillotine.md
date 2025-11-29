---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects:
  FixedDamage:
    Target: Targets
    Type: OneHitKO
Attributes:
  AccuracyReduction: -5
  Lethal: true
Category: Physical
Damage1: '-'
Damage2: ''
Description: "Fueled by the spirit of revolution the Pok\xE9mon sentences their foe\
  \ to be reduced at the neck. This devastating attack requires an emergency trip\
  \ to the Pok\xE9mon Center...and a basket."
Effect: Single Target. Low Accuracy 5. Deal Damage equal to the Target's Remaining
  HP, plus 1 Lethal Damage.
Name: Guillotine
Power: 0
Target: Foe
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