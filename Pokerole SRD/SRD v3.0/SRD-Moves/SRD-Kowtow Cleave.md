---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  CutterMove: true
  Lethal: true
  NeverMiss: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user gets on their knees and bows to its foe, then as the foe accepts
  this courtesy, a treacherous slash reveals the evil intent of the ruse.
Effect: Single Target. Lethal. Cutter Move. Never Miss.
Name: Kowtow Cleave
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