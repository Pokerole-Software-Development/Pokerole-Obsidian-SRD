---
Accuracy1: Insight
Accuracy2: Brawl/Intimidate
AddedEffects: {}
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user gets angry and throws a tantrum against the foe. The more the
  battle continues the angrier the user gets.
Effect: Single Target. If a foe damages the User with a Physical or Special Move in
  the same round after using this Move. Increase the User's Strength by 1. This effect
  can stack up to 3 Times.
Name: Rage
Power: 1
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