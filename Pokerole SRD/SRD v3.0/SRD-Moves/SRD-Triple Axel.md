---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  AccuracyReduction: 1
  TripleAction: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: A series of cold-blooded kicks that break bone as they would break brittle
  ice.
Effect: Single Target. Triple Action. *Add 1 Extra Die to the Damage of the 2nd hit
  and 2 Extra Dice to the Damage of the 3rd hit. **Second hit has Low Accuracy 1.
  ***Third hit has Low Accuracy 2.
Name: Triple Axel
Power: 1
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