---
Accuracy1: Special
Accuracy2: Channel/Nature
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: ReflectType
Attributes:
  Duration: wholeScene
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon is able to rewrite their own cellular composition at\
  \ will to match that of potential predators. Increasing chances of survival."
Effect: Target Self. Change the User's Type to match the one(s) of a foe. (ie Staryu
  is battle vs Charizard, their type will become Fire/Flying intead of Water) Whole
  Scene Duration.
Name: Reflect Type
Power: 0
Target: Self
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