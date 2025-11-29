---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 2
    Type: Flinch
Attributes:
  WindMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: "A raging twister embedded with a dragon\u2019s fury. No one wants to\
  \ be trapped in this fearsome spiral, which almost touches the sky."
Effect: Target all foes in Range. Wind Move. Roll 2 Chance dice to Flinch those affected.
  If the Target is Out of Range due to using "Fly", "Bounce" or "Sky Drop" this Move
  hits anyways.
Name: Twister
Power: 2
Target: All Foes
Type: Dragon
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