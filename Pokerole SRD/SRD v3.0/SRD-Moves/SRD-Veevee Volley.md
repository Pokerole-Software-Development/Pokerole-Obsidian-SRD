---
Accuracy1: Dexterity
Accuracy2: Athletic
AddedEffects: {}
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: Happiness
Description: "Long sessions playing Volley ball with your Pok\xE9mon make it very\
  \ happy. During battle, it just replaces the ball with a foe."
Effect: Single Target. *Add 1 Extra Die to the Damage Pool of this Move for every
  point of Happiness on the User, up to 5 Dice may be added this way. If the user
  of this Move is at its Final Stage of Evolution, this move fails.
Name: Veevee Volley
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