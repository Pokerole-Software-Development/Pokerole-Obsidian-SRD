---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Duration: 1
  SoundMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: "Shouts, screams, and loud music... What does a Pok\xE9mon have to do\
  \ here for a peaceful night of sleep?"
Effect: 'Target Random Foe. Sound Move. This Effect Targets the Battle Field: Pokemon
  will be cured of the Sleep Status. Duration 1 Round.'
Name: Uproar
Power: 3
Target: Random Foe
Type: Normal
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