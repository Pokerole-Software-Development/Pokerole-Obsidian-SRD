---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects:
  StatChanges:
  - Affects: Targets
    ChanceDice: 1
    Stages: -1
    Stats:
    - Def
Attributes:
  CutterMove: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon sharpens a seashell to use as a cutting tool, when this\
  \ shell manages to cut through the foe\u2019s armor, they\u2019ll finally will have\
  \ mastered the craft."
Effect: Single Target. Cutter Move. Roll 1 Chance Die to Reduce the Target's Defense
  by 1.
Name: Razor Shell
Power: 3
Target: Foe
Type: Water
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