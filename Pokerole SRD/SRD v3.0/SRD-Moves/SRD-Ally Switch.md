---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Reaction: '3'
  SwitcherMove: User
Category: Support
Damage1: ''
Damage2: ''
Description: "The user vanishes just as they were about to be hit, and suddenly there\u2019\
  s another Pok\xE9mon in their place. Di-Did the user disappear? Or was it never\
  \ there to begin with?"
Effect: Target Self. Reaction 3. Switcher Move for the User. If successful, restore
  the Action this Move costed and the switched ally may use a Reaction when they enter
  the field.
Name: Ally Switch
Power: 0
Target: Self
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