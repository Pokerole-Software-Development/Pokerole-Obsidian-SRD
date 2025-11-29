---
Accuracy1: Clever
Accuracy2: Nature
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Tailwind
Attributes:
  Duration: 4
  WindMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: "Flying Pok\xE9mon know better than anyone how to use the wind in their\
  \ favor. Let its draft carry you to victory."
Effect: Target User's side of the Field. Wind Move. Increase by 2 the Dexterity of
  everyone on the User's side of the field. Duration 4 Rounds.
Name: Tailwind
Power: 0
Target: Ally's Battlefield
Type: Flying
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