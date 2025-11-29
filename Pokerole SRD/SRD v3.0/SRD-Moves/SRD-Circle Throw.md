---
Accuracy1: Vitality
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  AccuracyReduction: -1
  LateReaction: '1'
  SwitcherMove: Foe
  SwitcherMoveForFoe: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "Using their best sumo moves, the Pok\xE9mon throws the foe 60ft. out\
  \ of the battlefield."
Effect: Single Target. Low Accuracy -1. Late Reaction 1. Switcher Move for the foe.
Name: Circle Throw
Power: 2
Target: Foe
Type: Fighting
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