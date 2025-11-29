---
Accuracy1: Insight
Accuracy2: Nature
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -1
    Stats:
    - Dexterity
Attributes:
  EntryHazard: true
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon quickly covers the arena with a sticky web, newly arrived\
  \ foes will have trouble moving with ease."
Effect: Target's Foe's Side of the Field. Entry Hazard. Reduce by 1 the Dexterity
  of Foes that enter the battlefield. Pokemon with Immunity to Ground are not affected.
Name: Sticky Web
Power: 0
Target: Foe's Battlefield
Type: Bug
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