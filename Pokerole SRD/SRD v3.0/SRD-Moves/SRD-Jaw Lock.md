---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Block
  - Affects: User
    Type: Block
Attributes:
  BiteMove: true
  Duration: wholeScene
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The user will capture its foe in a crushing jaw grip. It won\u2019t\
  \ let go no matter how much you try to separate them. The only way it will release\
  \ its victim is if one of them faints."
Effect: Single Target. Bite Move. Blocks both User and Target. Whole Scene Duration.
Name: Jaw Lock
Power: 3
Target: Foe
Type: Dark
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