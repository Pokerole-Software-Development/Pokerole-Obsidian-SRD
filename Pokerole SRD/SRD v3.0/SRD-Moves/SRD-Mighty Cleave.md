---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  CutterMove: true
  IgnoreShield: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "With a mighty light, the Pok\xE9mon cleaves through the foe\u2019s protections\
  \ and strikes like a boulder."
Effect: Single Target. Cutter Move. Ignore Shield Moves & Force Fields active on the
  foe or their side of the field.
Name: Mighty Cleave
Power: 4
Target: Foe
Type: Rock
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