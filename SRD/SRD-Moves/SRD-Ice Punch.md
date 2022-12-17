---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 1
    Type: Freeze
Attributes:
  FistBased: true
Damage1: Strength
Damage2: ''
Description: The Pokemon delivers a strike covered in ice. The user's hands can freeze
  anything they touch.
DmgType: Physical
Effect: Fist Based. Roll 1 Chance Dice to Freeze the foe.
Name: Ice Punch
Power: 3
Target: Foe
Type: Ice
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