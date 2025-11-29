---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Lethal: true
  ResistedWithDefense: true
  Unique: true
Category: Special
Damage1: Special
Damage2: ''
Description: Through sheer psychic power, the user materializes its energy to deal
  a heavy strike to its foe.
Effect: Single Target. Lethal. Unique. This Move is resisted with the Foe's Defense
  instead of its Sp. Defense.
Name: Psystrike
Power: 4
Target: Foe
Type: Psychic
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