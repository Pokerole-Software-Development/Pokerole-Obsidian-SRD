---
Accuracy1: Will
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Duration: wholeScene
  Lethal: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The User unleashes all of its might through a massive blast of raging\
  \ fire. Although the damage is devastating the Pok\xE9mon is left unable to produce\
  \ more fire for a while."
Effect: Single Target. Lethal. After damage is dealt, the user loses its Fire-Type.
  If its only type was Fire, it is now Typeless. User's Physical & Special Fire-Type
  Moves have Power 0. Whole Scene Duration. This effect does not end by switching
  out the User.
Name: Burn Up
Power: 7
Target: Foe
Type: Fire
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