---
Accuracy1: Insight
Accuracy2: Stealth
AddedEffects: {}
Attributes:
  IgnoreDefenses: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "Bit by bit the Pok\xE9mon finds an opening though all layers of defense\
  \ their target has until there is nothing left to protect it from a direct strike."
Effect: 'Single Target. Ignore Cover & Substitute decoys. Ignore Defenses. Remove
  effects that increase Evasion Actions from the Target (ie Moves like: Double Team,
  Minimize. Abilities like: Sand Veil) '
Name: Chip Away
Power: 2
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