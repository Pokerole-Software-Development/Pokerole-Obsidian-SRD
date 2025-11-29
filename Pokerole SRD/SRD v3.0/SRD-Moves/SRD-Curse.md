---
Accuracy1: Will
Accuracy2: Stealth/Intimidate
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Curse
Attributes:
  Duration: Permanent
Category: Support
Damage1: ''
Damage2: ''
Description: "The user mutters an evil incantation, misery will befall into the foe\
  \ at the cost of the user\u2019s soul. To get rid of the curse, perform an exorcism\
  \ or get help at a Pok\xE9mon Center"
Effect: Single Target. Roll half of the User's HP as Typeless Damage Dice to itself,
  ignoring defenses. The Target will remove 1 success from all of their Rolls until
  the Curse if lifted.
Name: Curse
Power: 0
Target: Foe
Type: Ghost
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