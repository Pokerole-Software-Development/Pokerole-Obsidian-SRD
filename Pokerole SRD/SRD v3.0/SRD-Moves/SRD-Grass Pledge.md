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
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon chants to invoke the power of grass, their pledge is\
  \ heard and the ground crumbles as vegetation grapples and traps everyone in the\
  \ field."
Effect: 'Area Move. Reduce by 1 the Dexterity of those affected. This Effect Targets
  the Battle Field: Entry Hazard. Reduce by 1 the Dexterity of Target''s that enter
  the battlefield. Pokemon with Immunity to Ground are not affected.'
Name: Grass Pledge
Power: 3
Target: Area
Type: Grass
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