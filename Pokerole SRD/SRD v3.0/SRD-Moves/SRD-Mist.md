---
Accuracy1: Special
Accuracy2: Nature/Stealth
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Mist
Attributes:
  Duration: 4
Category: Support
Damage1: ''
Damage2: ''
Description: "A thick layer of mist cloaks a pack of pok\xE9mon, those with the intent\
  \ to trick and weaken them will have to find them first."
Effect: Target User and Allies in Range. Targets cannot have their Attributes or Traits
  Reduced. Previously Reduced Attributes and Traits remain. Duration 4 Rounds.
Name: Mist
Power: 0
Target: All Allies
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