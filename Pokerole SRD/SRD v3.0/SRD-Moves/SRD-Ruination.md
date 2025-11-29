---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects: {}
Attributes:
  IgnoreDefenses: true
  Lethal: true
  Unique: true
Category: Special
Damage1: Varies
Damage2: ''
Description: "The Pok\xE9mon summons a disaster to befall onto their victim, few make\
  \ it out alive, and those who do don\u2019t stay that way for long."
Effect: Single Target. Unique. Lethal. Roll Damage dice equal to the Target's Total
  HP. Ignore Defenses. This move will fail if the Target has been previously hit with
  this Move during the Battle.
Name: Ruination
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