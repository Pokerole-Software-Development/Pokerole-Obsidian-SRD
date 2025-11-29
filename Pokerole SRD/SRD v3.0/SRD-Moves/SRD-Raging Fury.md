---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  PhysicalRanged: true
  Rampage: true
  Ranged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon goes mad with rage, spitting fire viciously all over\
  \ the battlfield and barely recognizing friend from foe."
Effect: Target Random foe. Ranged. Rampage.
Name: Raging Fury
Power: 5
Target: Random Foe
Type: Fire
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