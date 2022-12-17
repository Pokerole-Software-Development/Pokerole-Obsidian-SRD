---
Accuracy1: Dexterity
Accuracy2: Stealth
AddedEffects:
  Ailments:
  - Affects: Target
    Rounds: 4
    Type: Block
Attributes: {}
Damage1: Strength
Damage2: ''
Description: The user is so flat that you can barely see it in the tall grass, it
  is just waiting for its foe to get close enough to use its body as a snare trap.
DmgType: Physical
Effect: Target is Blocked for the Next 4 Rounds.
Name: Snap Trap
Power: 2
Target: Foe
Type: Grass
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