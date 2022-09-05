---
Accuracy1: Dexterity
Accuracy2: Brawl
Damage1: Strength
Damage2: ''
Description: The User flails and struggles to survive. The more weakened it is the
  stronger this attack will be.
DmgType: Physical
Effect: Add 1 Dice to the Damage Roll for every missing HP the user has. Up to +5
  Dice may be added this way.
Name: Flail
Power: 1
Target: Foe
Type: Normal
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