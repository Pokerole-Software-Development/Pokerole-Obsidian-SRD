---
Accuracy1: Insight
Accuracy2: Intimidate
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: CenterOfAttention
Attributes:
  PowderMove: true
  Reaction: '2'
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon releases an irritating powder that itches and enrages\
  \ its foes into full-attack mode."
Effect: Target Self. Reaction 2. Powder Move. All of the Foe's Physical and Special
  Moves will Target the user if able. Duration 1 Round.
Name: Rage Powder
Power: 0
Target: Self
Type: Bug
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