---
Accuracy1: Dexterity
Accuracy2: Brawl
Damage1: Strength
Damage2: ''
Description: The Pokemon uses its fangs to viciously tear whatever it is biting.
DmgType: Physical
Effect: Lethal. Roll 1 Chance Dice to reduce foe's Defense.
Name: Crunch
Power: 3
Target: Foe
Type: Dark
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