---
Accuracy1: Dexterity
Accuracy2: Channel
Damage1: Special
Damage2: ''
Description: The Pokemon attacks with a pulsing blast of water, this leaves the foe
  feeling dizzy.
DmgType: Special
Effect: Roll 3 Chance Dice to Confuse the foe.
Name: Water Pulse
Power: 2
Target: Foe
Type: Water
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