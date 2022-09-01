---
Accuracy1: DEXTERITY
Accuracy2: CHANNEL
Damage1: SPECIAL
Damage2: ''
Description: The user shouts loudly and the echo answers back, it will yell louder
  every time the echo talks back.
DmgType: SPECIAL
Effect: Sound Based. This move can be used many times in the same Round. Add 1 Extra
  Dice to the Damage Pool for every consecutive time you use it. Up to 8 dice may
  be added this way. Reset the effect if the user performs another move, evasion,
  or clash.
Name: Echoed Voice
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