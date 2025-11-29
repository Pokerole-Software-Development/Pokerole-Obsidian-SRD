---
Accuracy1: Dexterity
Accuracy2: Stealth
AddedEffects: {}
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon\u2019s spirit possesses an Item and attacks with that\
  \ cursed object. It is said that if the Pok\xE9mon lingers too long possesing an\
  \ object, it\u2019ll have trouble getting out."
Effect: Single Target. Can only be used if the Target is Holding an Item or if Items
  have been used on the Target's side of the field.
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

| Type          | Target          | Category          | Power          |
| ------------- | --------------- | ----------------  | -------------- |
| `= this.Type` | `= this.Target` | `= this.Category` | `= this.Power` | 

**Effect:** `= this.Effect`