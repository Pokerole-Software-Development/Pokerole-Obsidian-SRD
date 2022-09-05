---
Accuracy1: Dexterity
Accuracy2: Stealth
Damage1: ''
Damage2: ''
Description: The Pokemon dissapears in a poof of smoke. When the smoke vanishes, an
  object identical to the user remains in its place to shield it from harm. It looks
  amazingly real.
DmgType: Support
Effect: Deal 2 Damage to the user and put a decoy with 2 HP with the same Defenses
  as the user. If the decoy's HP is depleted, it disappears and the user comes back
  into the fight. Decoy can only be affected by damaging moves.
Name: Substitute
Power: 0
Target: User
Type: Normal
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