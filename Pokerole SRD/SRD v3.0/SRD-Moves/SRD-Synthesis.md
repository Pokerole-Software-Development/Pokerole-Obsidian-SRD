---
Accuracy1: Vitality/Insight
Accuracy2: Nature
AddedEffects:
  Heal:
    Target: Targets
    Type: Basic
    WillPointCost: 1
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon gathers sunlight to re-energize themselves."
Effect: Target Self. Basic Heal. If successful, spend 1 Will Point to activate. If
  Sunny Weather is in effect, this Move becomes a Complete Heal. If performed under
  Rain, Sandstorm, Hail or Snowy Weather, this Move is a Minor heal and only heals
  1 HP.
Name: Synthesis
Power: 0
Target: Self
Type: Grass
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