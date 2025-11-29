---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects:
  StatChanges:
  - Affects: Targets
    ChanceDice: 3
    Stages: -1
    Stats:
    - Def
Attributes:
  AccuracyReduction: -3
Category: Physical
Damage1: Strength
Damage2: ''
Description: "With a hardened tail, the Pok\xE9mon swings against the foe to make\
  \ a dent in their armor."
Effect: Single Target. Low Accuracy 3. Roll 3 Chance Dice to Reduce the Target's Defense
  by 1.
Name: Iron Tail
Power: 4
Target: Foe
Type: Steel
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