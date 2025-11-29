---
Accuracy1: Tough/Cool
Accuracy2: Intimidate
AddedEffects: {}
Attributes:
  Reaction: '2'
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon makes a dramatic entrance to the battlefield, taking\
  \ the foe by surprise."
Effect: Single Target. Reaction 2. This Move will only work on the First Round the
  User is out in battle. From the second round on, it will fail automatically.
Name: First Impression
Power: 3
Target: Foe
Type: Bug
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