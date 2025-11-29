---
Accuracy1: Insight
Accuracy2: Perform
AddedEffects: {}
Attributes:
  Unique: true
  UserFaints: true
Category: Support
Damage1: ''
Damage2: ''
Description: "The moon shines at the darkest hours, reflecting sun\u2019s life bringer\
  \ light on those fallen into the night. Cresselia takes pity of their lost souls\
  \ and guides them towards the dawn."
Effect: Target Self. Unique. Roll the User's Remaining HP as Typeless Damage dice
  to itself. One allied Target restores its full HP and it is cured from any Status
  Condition, if it was fainted, restore conciousness. If the chosen Target is not
  in-battle, it is called out and ready to fight with the same remaining actions as
  the user.
Name: Lunar Dance
Power: 0
Target: Self
Type: Psychic
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