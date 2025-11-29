---
Accuracy1: Will
Accuracy2: Nature
AddedEffects: {}
Attributes:
  Duration: wholeScene
Category: Support
Damage1: ''
Damage2: ''
Description: "The user lays the forest\u2019scurse upon the target, causing roots\
  \ and branches to grow on its body until they are a haunted tree. Perform an exorcism\
  \ or get to a Pok\xE9mon Center ASAP"
Effect: Single Target. Add the Grass Type to the Target's Type. (ie Pikachu will now
  be "Electric/Grass", Charizard will not be "Fire/Flying/Grass") If the Target already
  has a third Type attached, replace it.
Name: Forest's Curse
Power: 0
Target: Foe
Type: Grass
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