---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  HighCritical: true
  Lethal: true
  Unique: true
Category: Special
Damage1: Special
Damage2: ''
Description: "A dark wind rises, turning everything it touches into dust to be scattered\
  \ until nothing remains. People, Pok\xE9mon, plants, everything fades like a distant\
  \ memory."
Effect: Single Target. Lethal. High Critical. Unique.
Name: Oblivion Wing
Power: 4
Target: Foe
Type: Flying
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