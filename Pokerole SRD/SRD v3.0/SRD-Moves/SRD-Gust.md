---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  WindMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon flaps their wings and strikes the foe with a swirl of\
  \ wind. Pok\xE9mon in the air may get swept away"
Effect: Single Target. Wind Move. If the Target is Out of Range due to using "Fly",
  "Bounce" or "Sky Drop", this Move hits anyway.
Name: Gust
Power: 2
Target: Foe
Type: Flying
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