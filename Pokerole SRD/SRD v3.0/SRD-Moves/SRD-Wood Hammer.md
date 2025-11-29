---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  Recoil: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon creates a giant wooden hamer and it uses it to smash\
  \ the foe with such force the hammer also explodes into wood splinters."
Effect: Single Target. Recoil.
Name: Wood Hammer
Power: 5
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