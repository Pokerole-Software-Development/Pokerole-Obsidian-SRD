---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Paralyze
Attributes:
  AccuracyReduction: 3
  Lethal: true
Damage1: Special
Damage2: ''
Description: The user hurls a dreadful bombardment of electric explosions. Anyone
  hit won't be able to move for a very long time.
DmgType: Special
Effect: Lethal. Paralyze the Foe. -3 Accuracy.
Name: Zap Cannon
Power: 5
Target: Foe
Type: Electric
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