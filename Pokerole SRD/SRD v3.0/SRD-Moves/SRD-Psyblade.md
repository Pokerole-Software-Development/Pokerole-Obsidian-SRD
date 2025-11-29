---
Accuracy1: Dexterity/Insight
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  CutterMove: true
  Lethal: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon attacks using an ethereal blade. Electric energy will\
  \ increase the sharpness of its edge."
Effect: Single Target. Lethal. Cutter Move. *If Electric Terrain is active, add 2
  Extra Dice to the Damage pool of this Move.
Name: Psyblade
Power: 3
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