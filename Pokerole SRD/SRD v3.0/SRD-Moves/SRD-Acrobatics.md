---
Accuracy1: Dexterity
Accuracy2: Athletic
AddedEffects: {}
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon is quick and graceful, they cartwheel, contort and make\
  \ a double back jump before landing onthe foe. Their best perfomance is done when\
  \ they are unburdened."
Effect: Single Target. *If the User has a Held Item, Reduce 2 Dice to the Damage Pool
  of this Move.
Name: Acrobatics
Power: 4
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