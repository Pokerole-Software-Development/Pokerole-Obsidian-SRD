---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  CutterMove: true
  DoubleAction: true
  Lethal: true
  NeverMiss: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon swings with a sword so sharp, it cuts twice."
Effect: Single Target. Cutter Move. Lethal. Never Miss. Double Action.
Name: Tachyon Cutter
Power: 2
Target: Foe
Type: Steel
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