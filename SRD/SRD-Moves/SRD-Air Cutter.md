---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  HighCritical: true
Damage1: Special
Damage2: ''
Description: The user will send out a wave of sharp wind that will harm anything it
  touches.
DmgType: Special
Effect: Target all foes in Range. High Critical.
Name: Air Cutter
Power: 2
Target: All Foes
Type: Flying
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