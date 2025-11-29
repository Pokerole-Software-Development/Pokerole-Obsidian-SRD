---
Accuracy1: Insight
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  IgnoreDefenses: true
  LateReaction: '5'
Category: Physical
Damage1: Varies
Damage2: ''
Description: "The Pok\xE9mon strikes back at their foe. Showing they can take a hit\
  \ and punch even harder."
Effect: Single Target. Late Reaction 5. Can only be used if Target's last Move on
  User was a Physical Move. For damage, roll dice equal to Target's last damage pool
  rolled against the User plus 2 dice. Ignore Defenses.
Name: Counter
Power: 0
Target: Foe
Type: Fighting
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