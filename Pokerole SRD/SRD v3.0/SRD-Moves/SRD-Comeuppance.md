---
Accuracy1: Insight
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  IgnoreDefenses: true
Category: Physical
Damage1: Varies
Damage2: ''
Description: An eye for en eye, the user retaliates with a vengance against those
  who cross them.
Effect: Single Target. Can only be used if Target's last Move on User was a Physical
  or Special Move. Roll dice equal to Target's last damage pool rolled against the
  User plus 2 dice.
Name: Comeuppance
Power: 0
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