---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Lethal: true
  Unique: true
Category: Dual
Damage1: Strength/Special
Damage2: ''
Description: "The Pok\xE9mon attacks with a large pillar of light that comes out from\
  \ they stand, either the blazing energy or the crushing strike are enough to knock\
  \ foes out."
Effect: Single Target. Lethal. Unique. This Move's Damage Pool, can be rolled with
  either Strength or Special Attribute, dealing Physical or Special Damage respectively.
  Choose whatever is most convenient for the user.
Name: Photon Geyser
Power: 4
Target: Foe
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