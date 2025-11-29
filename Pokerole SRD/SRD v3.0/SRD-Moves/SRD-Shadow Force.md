---
Accuracy1: Strength
Accuracy2: Stealth
AddedEffects: {}
Attributes:
  Charge: true
  IgnoreShield: true
  Lethal: true
  Unique: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon dissapears into a dark dimension to strike its foe at\
  \ the next opportunity. The blow will hurt the target not on their body but directly\
  \ into their soul."
Effect: Single Target. Charge move. Out of Range while Charging. Lethal. Unique. Ignore
  Defenses and any Shield Moves and Force Fields active on the Target. Damage dealt
  by this Move cannot be healed for 24 hrs.
Name: Shadow Force
Power: 5
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