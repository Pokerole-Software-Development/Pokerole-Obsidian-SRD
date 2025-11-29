---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  Ailments:
  - Affects: Targets
    Rounds: 4
    Type: AquaRingLifeDew
Attributes:
  Duration: wholeScene
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon coats themselves in fresh water."
Effect: Target Self. The User heals 1 HP at the end of each Round. Spend 1 Will point
  to activate. Whole Scene Duration.
Name: Aqua Ring
Power: 0
Target: Self
Type: Water
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