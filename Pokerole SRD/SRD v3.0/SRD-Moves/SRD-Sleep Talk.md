---
Accuracy1: Varies
Accuracy2: ''
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: Varies
Damage2: ''
Description: "Despite being asleep, the Pok\xE9mon keeps dreaming about the battle.\
  \ They talk incoherences and even sleep walk."
Effect: If the user is not asleep, this Move fails. Instead of making a roll to try
  to wake up, the user may choose to use Sleep Talk instead. Choose a Move on the
  user's Move set at random and Target Random foe with it. Sleep Talk can be repeated
  up to 5 times per Round.
Name: Sleep Talk
Power: 0
Target: Random Foe
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