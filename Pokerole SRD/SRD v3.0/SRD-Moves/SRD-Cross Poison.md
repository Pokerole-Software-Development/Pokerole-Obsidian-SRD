---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 1
    Type: Poison
Attributes:
  CutterMove: true
  HighCritical: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon releases a powerful acidic gas that melts all inorganic\
  \ matter in seconds."
Effect: Single Target. Cutter Move. High Critical. Roll 1 Chance Die to Poison the
  Target.
Name: Cross Poison
Power: 3
Target: Foe
Type: Poison
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