---
Accuracy1: Vitality
Accuracy2: Nature
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "One Pok\xE9mon\u2019s trash is another one\u2019s treasure."
Effect: Target Self. The Pokemon reuses an Item (Berries, Potions, Full Heal, etc.)
  that has already been spent during the battle on any side of the battlefield. Recycle
  can't be used more than 3 times per battle by the User.
Name: Recycle
Power: 0
Target: Self
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