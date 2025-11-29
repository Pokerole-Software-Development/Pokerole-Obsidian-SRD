---
Accuracy1: Tough/Clever
Accuracy2: Intimidate
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Torment
Attributes:
  Duration: 4
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon bullies their foe to the point of torment where they\
  \ cannot keep using their strategy without feeling bad about it."
Effect: Single Target. The Target cannot use any of the Moves it used during the last
  Round. Duration 4 Rounds.
Name: Torment
Power: 0
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