---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  Lethal: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon quite literally squeezes the life out of their foe. But\
  \ to do this effectively they require to be in top condition."
Effect: Single Target. Lethal. *Remove 1 Dice from the Damage Pool for every missing
  HP on the target. Up to 4 Dice may be removed this way.
Name: Wring Out
Power: 5
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