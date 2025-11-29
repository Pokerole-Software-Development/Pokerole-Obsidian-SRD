---
Accuracy1: Insight
Accuracy2: Channel/Intimidate
AddedEffects: {}
Attributes:
  Unique: true
Category: Special
Damage1: Special
Damage2: ''
Description: "This chain contains the most potent neurotoxin currently known. It boosts\
  \ physical appearance, yet totally suppresses the mind and soul, turning the target\
  \ into the user\u2019s puppet."
Effect: Single Target. Unique. Roll 5 Chance Dice to Badly Poison the Target. At the
  end of the Round, if the Target was Poisoned by this Move, roll their Loyalty, get
  at least 3 successes, if it fails, from the next Round the Target becomes the user's
  Ally untl the poison is healed.
Name: Malignant Chain
Power: 4
Target: Foe
Type: Poison
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