---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Poison
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user spins around the field, cutting through obstacles and shooting
  small darts full of a toxic venom. The earth is now poisoned and left barren.
Effect: All Foes in Range. Poison those Affected. Remove Entry Hazards, Terrains (ie
  Grassy Terrain, Misty Terrain), Ongoing Damage and Leech seed from the User or their
  side of the field.
Name: Mortal Spin
Power: 2
Target: All Foes
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