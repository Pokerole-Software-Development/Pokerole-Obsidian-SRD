---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: 1
    Stats:
    - Dexterity
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon makes a swift spin to strike at the foe and in the process\
  \ everything laying close to the user is scattered out of the battlefield."
Effect: Single Target. Increase the User's Dexterity by 1. Remove Entry Hazards, Terrains
  (ie Grassy Terrain, Misty Terrain), Ongoing Damage and Leech seed from the User
  and/or their side of the field.
Name: Rapid Spin
Power: 2
Target: Foe
Type: Normal
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