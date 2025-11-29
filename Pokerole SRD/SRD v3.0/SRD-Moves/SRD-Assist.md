---
Accuracy1: Insight
Accuracy2: Etiquette
AddedEffects: {}
Attributes:
  CopyMove: true
  Unique: true
Category: Support
Damage1: ''
Damage2: ''
Description: "The user hurriedly remembers actions performed by others and mimics\
  \ them. Some Pok\xE9mon can even imitate human tasks and help carry them out."
Effect: Target One Ally. Copy Move. Choose one Move known by an Ally or member of
  your party, who may or may not be active in battle. You may choose another Target(s)
  for the Move. Unique Moves can't be copied.
Name: Assist
Power: 0
Target: Ally
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