---
Accuracy1: Tough
Accuracy2: Intimidate
AddedEffects: {}
Attributes:
  Duration: wholeScene
Category: Support
Damage1: ''
Damage2: ''
Description: The user represses the foe through intimidation so it thinks twice before
  acting.
Effect: Single Target. Target's will go last in the Initiative Order. Whole Scene
  Duration. This effect does not end by switching out the affected Pokemon. If used
  again, the previous Target has their order in the initiative restored.
Name: Quash
Power: 0
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