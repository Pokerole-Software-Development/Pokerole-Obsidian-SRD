---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Reaction: '6'
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon summons lightning from the sky. A foe gathering energy\
  \ makes for the perfect rod for lightning to be attracted to it."
Effect: Single Target. Reaction 6. *This Move can only be used as a Reaction and only
  if the Target used a Physical or Special Move, otherwise it will fail.
Name: Thunderclap
Power: 3
Target: Foe
Type: Electric
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