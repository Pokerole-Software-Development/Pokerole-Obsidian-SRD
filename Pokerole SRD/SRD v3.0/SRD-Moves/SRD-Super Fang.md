---
Accuracy1: Strength/Dexterity
Accuracy2: Brawl
AddedEffects:
  FixedDamage:
    MaxValue: 10
    Target: Targets
    Type: HpPercentage
    Value: 0.5
Attributes:
  AccuracyReduction: -1
  BiteMove: true
  IgnoreDefenses: true
Category: Physical
Damage1: Varies
Damage2: ''
Description: "The Pok\xE9mon jumps to bite a chunk off their Target with their mighty\
  \ fangs. After each bite there\u2019s less and less foe to take chunks off."
Effect: Single Target. Low Accuracy 1. Bite Move. Roll Normal-Type Damage Dice equal
  to Half of the Target's remaining HP. Up to 10 Dice may be rolled this way. Ignore
  Defenses.
Name: Super Fang
Power: 0
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