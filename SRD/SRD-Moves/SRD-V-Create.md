---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: -1
    Stats:
    - Dexterity
    - Def
    - SpDef
Attributes: {}
Damage1: Strength
Damage2: ''
Description: The user slams its foe with a V-Shaped flame on its forehead. Upon impact,
  it detonates a terrible explosion and leaves the user pretty vulnerable afterwards.
DmgType: Physical
Effect: Reduce the user's Dexterity, Defense, and Sp. Defense.
Name: V-Create
Power: 7
Target: Foe
Type: Fire
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`