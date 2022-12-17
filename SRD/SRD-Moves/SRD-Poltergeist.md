---
Accuracy1: Dexterity
Accuracy2: Stealth
AddedEffects: {}
Attributes: {}
Damage1: Strength
Damage2: ''
Description: The Pokemon's spirit possesses an Item and attacks with that cursed object.
  It is said that if the Pokemon lingers too long possessing an object, it'll have
  trouble getting out.
DmgType: Physical
Effect: Can only be used if the Target is Holding an Item or if Items have been used
  on the Target's side of the field.
Name: Poltergeist
Power: 4
Target: Foe
Type: Ghost
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`