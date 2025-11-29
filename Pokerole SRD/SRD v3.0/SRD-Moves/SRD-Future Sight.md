---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: FutureSight
Attributes:
  IgnoreShield: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon foresees something terrible happening. Although when\
  \ it tries to see their own future, the images are ever changing."
Effect: Single Target. This Move's damage is dealt at the beginning of the next Round.
  Ignore Shield Moves, Force Field, Cover & Substitute. If the target restires or
  switches out from battle, the damage will be dealt to the next opponent or to one
  of its allies.
Name: Future Sight
Power: 5
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