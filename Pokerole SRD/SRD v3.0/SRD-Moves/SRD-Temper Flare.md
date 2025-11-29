---
Accuracy1: Strength
Accuracy2: Intimidate
AddedEffects: {}
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon is a hot-head whose temper grows ever fiercer when dealing\
  \ with frustration."
Effect: Single Target. *Add 2 Extra Dice to the Damage Pool of this Move is the User
  failed the Accuracy roll of the last Move it performed.
Name: Temper Flare
Power: 3
Target: Foe
Type: Fire
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