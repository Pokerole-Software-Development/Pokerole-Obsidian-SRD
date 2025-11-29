---
Accuracy1: Insight
Accuracy2: Intimidate
AddedEffects: {}
Attributes:
  AccuracyReduction: 1
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon charges against a foe, trampling through with a righteous\
  \ fury, a blazing rage, a cold wrath, or maybe just the senseless desire for violence."
Effect: Single Target. *The Type of this Move becomes the same as the User's Secondary
  Type if possible, otherwise their Main Type. This affects Weakness, Resistances
  and STAB accordingly.
Name: Raging Bull
Power: 3
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