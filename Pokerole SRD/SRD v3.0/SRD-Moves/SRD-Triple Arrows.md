---
Accuracy1: Dexterity
Accuracy2: Athletic
AddedEffects: {}
Attributes:
  HighCritical: true
  Ranged: true
  TripleAction: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "Three fast arrows shot in succession. The Pok\xE9mon who manages to\
  \ land all three in the exact same spot has become a true sniper."
Effect: Single Target. Ranged. Triple Action. Reduce the foe's Defense by 1. *If All
  3 hits land, all of the User's Physical and Special Moves now have the "High Critical"
  Effect, this effect has a whole scene duration.
Name: Triple Arrows
Power: 3
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