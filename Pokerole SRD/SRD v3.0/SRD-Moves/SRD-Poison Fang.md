---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 5
    Type: BadlyPoison
Attributes:
  BiteMove: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon goes for a quick bite, releasing the foe just as fast.\
  \ Let the poison slowly consume the foe from the inside out. No need to spend more\
  \ energy when a drop is more than enough."
Effect: Single Target. Bite Move. Roll 5 Chance Dice to Badly Poison the Target.
Name: Poison Fang
Power: 2
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