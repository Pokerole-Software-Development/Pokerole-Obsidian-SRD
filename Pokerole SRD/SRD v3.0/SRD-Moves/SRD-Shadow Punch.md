---
Accuracy1: Strength
Accuracy2: Brawl/Stealth
AddedEffects: {}
Attributes:
  FistMove: true
  NeverMiss: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon punches the air, inadvertently, their shadow delivers\
  \ the punch through the foe\u2019s own shadow. This move is impossible to predict."
Effect: Single Target. Never Miss. Fist Move.
Name: Shadow Punch
Power: 2
Target: Foe
Type: Ghost
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