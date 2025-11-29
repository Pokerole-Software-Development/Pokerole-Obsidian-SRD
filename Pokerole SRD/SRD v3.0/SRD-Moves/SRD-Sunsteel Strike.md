---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  IgnoreShield: true
Attributes:
  IgnoreShield: true
  Lethal: true
  Unique: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "You suddenly stop in your tracks as you see a bright and blinding light\
  \ coming towards you at great speed. You do not see what hits you before it\u2019\
  s all darkness."
Effect: Single Target. Lethal. Unique. If anything on the foe's side would prevent
  this move frm dealing (Pokemon Type, Abilities, Shield Moves, Weather or Force Fields),
  ignore it. This Move cannot be Clashed.
Name: Sunsteel Strike
Power: 4
Target: Foe's Battlefield
Type: Steel
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