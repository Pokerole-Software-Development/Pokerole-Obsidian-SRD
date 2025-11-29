---
Accuracy1: Dexterity
Accuracy2: Stealth
AddedEffects:
  Ailments:
  - Affects: Targets
    Rounds: 1
    Type: Diving
Attributes:
  Charge: true
  Vulnerable: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "Just look at the world around you right here on the ocean floor, such\
  \ wonderful things surround you. What more are you lookin\u2019 for?"
Effect: 'Single Target. Charge Move. Out of Range while Charging. Vulnerable while
  charging to: Scald/ Surf/ Whirlpool/ Freeze-Dry/ Sheer Cold. Out of battle allows
  the Pokemon to move underwater carrying someone without risk of drowning.'
Name: Dive
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