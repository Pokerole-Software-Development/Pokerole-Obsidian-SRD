---
Accuracy1: Dexterity
Accuracy2: Stealth
AddedEffects: {}
Attributes:
  NeverMiss: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user approaches inconspicuously, pretending to attack the foe directly,
  then actually hits the foe from behind.
Effect: Single Target. Never Miss.
Name: Feint Attack
Power: 2
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