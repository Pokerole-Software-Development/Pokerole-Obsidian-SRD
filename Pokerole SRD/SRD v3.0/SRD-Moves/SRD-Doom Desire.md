---
Accuracy1: Insight
Accuracy2: Charm
AddedEffects:
  Ailments:
  - Affects: Targets
    Rounds: 1
    Type: DoomDesire
Attributes:
  IgnoreShield: true
  Unique: true
Category: Special
Damage1: Special
Damage2: ''
Description: "Be careful what you wish for, this Pok\xE9mon will read your most intimate\
  \ wishes and make them come true in very twisted ways."
Effect: Single Target. Unique. This Move's damage is dealt at the beginning of the
  next Rund. Ignore Shield Moves, Force Field, Cover & Substitute decoys. If the target
  retires or switches out from battle, the damage will be dealt to the next opponent
  or to one of its allies. Extra effects may be added at Storyteller's Discretion.
Name: Doom Desire
Power: 6
Target: Foe
Type: Steel
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