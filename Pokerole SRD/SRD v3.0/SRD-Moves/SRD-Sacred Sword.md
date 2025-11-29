---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  CutterMove: true
  IgnoreDefenses: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user slashes at its target with a mighty blade. Theres no hide nor
  armor thick enough to resist its valorous steel.
Effect: Single Target. Cutter Move. Ignore Defenses.
Name: Sacred Sword
Power: 3
Target: Foe
Type: Fighting
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