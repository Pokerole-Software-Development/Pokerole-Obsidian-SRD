---
Accuracy1: Special
Accuracy2: Stealth
AddedEffects: {}
Attributes:
  IgnoreDefenses: true
  IgnoreShield: true
Category: Special
Damage1: SetDamage
Damage2: ''
Description: "The Pok\xE9mon makes use of a small but very destructive shock that\
  \ goes through any wall, layer or wall."
Effect: Single Target. This Move always inflict 1 Typeless damage. Ignore Defenses,
  Force Fields, Shield Moves, Cover, Out of Range, Type or Ability that would prevent
  this damage.
Name: Sonic Boom
Power: 0
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