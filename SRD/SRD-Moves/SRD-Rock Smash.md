---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  StatChanges:
  - Affects: Targets
    ChanceDice: 5
    Stages: -1
    Stats:
    - Def
Attributes: {}
Damage1: Strength
Damage2: ''
Description: A powerful hit that can crush rocks. Used against a foe it is sure to
  leave an awful bruise and a crack on its armor.
DmgType: Physical
Effect: Roll 5 Chance Dice to Reduce foe's Defense.
Name: Rock Smash
Power: 2
Target: Foe
Type: Fighting
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`