---
Accuracy1: Insight
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
Description: "The Pok\xE9mon uses the moon\u2019s power to heal their injuries."
Effect: Target Self. Basic Heal. If successful, spend 1 Will point to activate. Night
  Time and Sunny Weather increase it to Complete Heal. Rain, Sandstorm and Hail Weather
  reduceto Minor Heal of 1 HP.
Name: Moonlight
Power: 0
Target: Self
Type: Fairy
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