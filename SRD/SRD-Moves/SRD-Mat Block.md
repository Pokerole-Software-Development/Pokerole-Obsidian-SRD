---
Accuracy1: Dexterity
Accuracy2: Athletic
AddedEffects: {}
Attributes:
  ShieldMove: true
Damage1: ''
Damage2: ''
Description: The Pokemon uses a mat or something similar as a shield.
DmgType: Support
Effect: Shield. Reduce 3 Dice from the foe's Damage Pool. This Move only works the
  first Round the User has been out.
Name: Mat Block
Power: 0
Target: User and Allies
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