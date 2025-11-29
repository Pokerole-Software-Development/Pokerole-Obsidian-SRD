---
Accuracy1: Dexterity/Insight
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 2
    Type: Confuse
Attributes:
  FistMove: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon locates their enemy\u2019s balance point and lands a\
  \ swift punch that leaves the foe seeing a swirl of stars around its head."
Effect: Single Target. Fist Move. Roll 2 Chance Dice to Confuse the Target.
Name: Dizzy Punch
Power: 3
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