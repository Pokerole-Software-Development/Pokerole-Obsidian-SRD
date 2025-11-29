---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  Charge: true
  CutterMove: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon focuses the sunlight on its sharp leaves, then releases\
  \ the energy with a shattering cut."
Effect: Single Target. Charge Move. Cutter Move. If Sunny Weather is active, you skip
  this Move's Charge action. If performed under Rain, Sandstorm or Hail/Snowy Weather,
  this Move takes two actions to Charge.
Name: Solar Blade
Power: 6
Target: Foe
Type: Grass
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