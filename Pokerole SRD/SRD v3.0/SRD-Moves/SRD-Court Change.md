---
Accuracy1: Clever
Accuracy2: Etiquette
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon signals the referee for half-time, the referee complies\
  \ and both parties swap their sides of the field. Wait... we brought everything\
  \ with us, right?"
Effect: Target Battlefield. Swap any Force Fields, Entry Hazards and Effects on the
  Foe's side of the field (ie Tailwind, Grassy Terrain healing, Fire Pledge.) for
  those on the User's side.
Name: Court Change
Power: 0
Target: Battlefield
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