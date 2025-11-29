---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  HateBonus: true
Category: Physical
Damage1: Strength
Damage2: Missing happiness
Description: "A mistreated Pok\xE9mon grows vicious and uncaring, a Move fueled by\
  \ anger."
Effect: Single Target. *Add 1 Extra Die to the Damage Pool of this Move for every
  missing point of Happiness on the user. Up to 5 Dice may be added this way.
Name: Frustration
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