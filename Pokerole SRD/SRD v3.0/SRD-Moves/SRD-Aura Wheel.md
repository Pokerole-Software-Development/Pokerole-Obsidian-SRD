---
Accuracy1: Insight
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
Description: "The Pok\xE9mon happily runs into a wheel made of electricity that strikes\
  \ the foe. If the user is feeling hungry the wheel\u2019s energy is replaced by\
  \ a dark aura."
Effect: Single Target. Increase the user's Dexterity by 1. If the user of this Move
  is in "Hangry Form" this Move is considered Dark-Type.
Name: Aura Wheel
Power: 4
Target: Foe
Type: Electric
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