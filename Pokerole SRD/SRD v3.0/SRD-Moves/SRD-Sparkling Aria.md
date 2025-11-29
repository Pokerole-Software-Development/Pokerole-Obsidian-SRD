---
Accuracy1: Special
Accuracy2: Perform
AddedEffects: {}
Attributes:
  SoundMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon sings a beautiful melody, the song comes out as a sparkling\
  \ fountain, bursting upon impact and quenching any fire in its path."
Effect: Area Move. Sound Move. *If an effected Pokemon had any level of Burn Status
  Condition, heal it instead of dealing damage.
Name: Sparkling Aria
Power: 3
Target: Area
Type: Water
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