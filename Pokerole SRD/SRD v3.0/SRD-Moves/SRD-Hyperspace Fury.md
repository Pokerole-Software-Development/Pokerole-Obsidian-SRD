---
Accuracy1: Special
Accuracy2: Stealth
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: -1
    Stats:
    - Def
Attributes:
  IgnoreShield: true
  NeverMiss: true
  Unique: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon opens portals to attack with each one of its arms, bypassing\
  \ all defenses and making it impossible to escape; however, portals go both ways."
Effect: Single Target. Never Miss. Ignores the effect of any Force Field or Shield
  Move active on the foe's side. Reduce the User's Defense by 1.
Name: Hyperspace Fury
Power: 4
Target: Foe
Type: Dark
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