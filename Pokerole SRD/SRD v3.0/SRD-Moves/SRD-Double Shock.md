---
Accuracy1: Will
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Duration: wholeScene
  Lethal: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user lets out a colossal discharge of electricity, lightning connecting
  the sky and earth for way too long. However, the effort effectively depletes the
  energy reserves of the user.
Effect: Single Target. Lethal. After damage is dealt, the user loses its Electric-Type.
  If its only type was Electric, it is now Typeless. User's Physical & Special Electric-Type
  Moves have Power 0. Whole Scene Duration. This effect does not end by switching
  out the User.
Name: Double Shock
Power: 7
Target: Foe
Type: Electric
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