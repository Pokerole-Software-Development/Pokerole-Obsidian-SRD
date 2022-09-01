---
Accuracy1: DEXTERITY
Accuracy2: NATURE
Damage1: ''
Damage2: ''
Description: The Pokemon creates a powerful wind current that swirls the enemy around
  and sends it flying away.
DmgType: SUPPORT
Effect: Low Priority 6. In the wild the battle ends. In an official fight, the Pokemon
  switches out. If it's the last or only Pokemon the move fails. Switcher Move.
Name: Whirlwind
Power: 0
Target: Foe
Type: Normal
---

#PokeroleSRD/Moves

## `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`