---
Accuracy1: Clever
Accuracy2: Nature
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: TarShot
  StatChanges:
  - Affects: Targets
    Stages: -1
    Stats:
    - Dexterity
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon gushes a blob of black tar over its foe. The unfortunate\
  \ victim can barely move afterwards, keep it away from fire sources, tar is extremely\
  \ flammable."
Effect: Single Target. Reduce the Target's Dexterity by 1. For the Whole Scene, Fire-Type
  Moves deal Super-Effective damage against the Target.
Name: Tar Shot
Power: 0
Target: Foe
Type: Rock
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