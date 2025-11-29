---
Accuracy1: Strength
Accuracy2: Athletic/Brawl
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: -1
    Stats:
    - Dex
Attributes:
  Recoil: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon rides a tsunami-like wave an slams it against its target.\
  \ The crash is very destructive and the Pok\xE9mon may end up falling from the ride."
Effect: Single Target. Recoil. Reduce User's Dexterity by 1.
Name: Wave Crash
Power: 5
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