---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: User
    Type: PainSplitUser
  - Affects: Targets
    Type: PainSplitTarget
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user channels their pain into the foe to relieve their agony. The
  foe gets to feel the burn of the damage it has caused.
Effect: Single Target. Spend 1 Will Point to activate. *Deal up to 3 Typeless Damage
  to the Target, Heal 1 HP to the User for every Damage dealt this way. This Move
  Fails if the User has more than Half HP rounded down. This Move cannot reduce a
  Target to less than 1 HP.
Name: Pain Split
Power: 0
Target: Foe
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