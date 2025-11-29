---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 1
    Type: Freeze
Attributes:
  AccuracyReduction: -2
  Lethal: true
  NeverMiss: true
  WindMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: The user summons a turbulent and gelid wind that feels like ice daggers.
  A pleasant day may make it difficult to call upon, but beware if the temperatures
  go below zero.
Effect: All Foes in Range. Low Accuracy 2. Lethal. Wind Move. Roll 1 Chance Die to
  Freeze those affected. *Sunny Weather increases to Low Accuracy 4. **Hail/Snowy
  Weather remove Low Accuracy and adds the effect "Never Miss".
Name: Blizzard
Power: 5
Target: All Foes
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