---
Accuracy1: Insight
Accuracy2: Nature
AddedEffects: {}
Attributes:
  Charge: true
  Unique: true
Category: Support
Damage1: ''
Damage2: ''
Description: "Through a mystical conection this Pok\xE9mon absorbs the life force\
  \ of earth itself to increase its power."
Effect: Target Self. Charge Move. Unique. Increase by 2 the User's Dexterity, Special
  and Sp. Defense.
Name: Geomancy
Power: 0
Target: Self
Type: Fairy
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