---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  AccuracyReduction: -1
  LateReaction: '6'
  SwitcherMove: Foe
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon sends their opponent flying up to 100ft in the air with\
  \ a strong flick of their tail."
Effect: Single Target. Low Accuracy 1. Late Reaction 6. Switcher Move for the Foe.
  In the wild, the battle may end.
Name: Dragon Tail
Power: 2
Target: Foe
Type: Dragon
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