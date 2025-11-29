---
Accuracy1: Dexterity
Accuracy2: Perform
AddedEffects: {}
Attributes:
  SoundMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon yells at the void. Their echo answers. The Pok\xE9mon\
  \ yells louder and louder everytime the echo talks back."
Effect: Single Target. Sound Move. This Move can be used many times in the same Round.
  *Add 1 Extra Die to the Damage pool of this move for each time you use it. Up to
  8 Dice might be added this way. Reset this effect if the user performs another move,
  evasion or clash.
Name: Echoed Voice
Power: 2
Target: Foe
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