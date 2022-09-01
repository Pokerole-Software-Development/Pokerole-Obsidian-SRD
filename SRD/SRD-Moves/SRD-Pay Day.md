---
Accuracy1: DEXTERITY
Accuracy2: BRAWL
Damage1: STRENGTH
Damage2: ''
Description: This move grants good fortune, making it more likely to get more money
  after each battle.
DmgType: PHYSICAL
Effect: 'Ranged. At the end of the battle give Money to the Trainer Equal to its Rank:
  Starter/Beginner - $20.00 Amateur - $50.00 Ace - $75.00 Pro - $100.00'
Name: Pay Day
Power: 2
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