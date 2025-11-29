---
Accuracy1: Dexterity
Accuracy2: Athletic
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Paralyze
Attributes:
  Recoil: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon charges their most powerful electric attack but instead\
  \ of releasing it, they run at top speed to crash agains their foe with it."
Effect: Single Target. Recoil. Roll 3 Chance die to Paralyze the Target.
Name: Volt Tackle
Power: 5
Target: Foe
Type: Electric
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