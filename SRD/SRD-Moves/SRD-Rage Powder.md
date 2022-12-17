---
Accuracy1: Insight
Accuracy2: Intimidate
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: CenterOfAttention
Attributes:
  Priority: 2
Damage1: ''
Damage2: ''
Description: The Pokemon releases an irritating powder that annoys and enrages foes
  into attacking.
DmgType: Support
Effect: Priority 2. During this Round, all damage moves from any foe must target the
  User.
Name: Rage Powder
Power: 0
Target: User
Type: Bug
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