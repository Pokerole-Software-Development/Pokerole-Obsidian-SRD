---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  CutterMove: true
  SuccessiveActions: true
Category: Physical
Damage1: Strength/Dexterity
Damage2: ''
Description: "The Pok\xE9mon uses their claws or scythes to rapidly cut as if shredding\
  \ paper."
Effect: Single Target. Successive Actions. Cutter Move.
Name: Fury Cutter
Power: 1
Target: Foe
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