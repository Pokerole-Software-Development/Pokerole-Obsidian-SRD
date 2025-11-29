---
Accuracy1: Strength/Insight
Accuracy2: Nature
AddedEffects: {}
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon creates a club out of thorny ivy vines, this club is\
  \ infused with the power of nature, everchanging."
Effect: Single Target. *The Type of this Move becomes the same as the User's Secondary
  Type if possible Otherwise their Main Type. This affects Weakness, Resistances,
  and STAB accordingly.
Name: Ivy Cudgel
Power: 3
Target: Foe
Type: Grass
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