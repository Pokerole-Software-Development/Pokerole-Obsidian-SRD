---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  AlwaysCrit: true
  FistMove: true
  Lethal: true
  Unique: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The \u201CDark Style\u201D is known as the most deadly and vicious of\
  \ battle techniques. The user mastered this style and their punches are wicked strong."
Effect: Single Target. Lethal. Fist Move. If the Accuracy Roll is successful, this
  Move becomes a Critical Hit.
Name: Wicked Blow
Power: 3
Target: Foe
Type: Dark
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