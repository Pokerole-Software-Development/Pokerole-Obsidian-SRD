---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  PhysicalRanged: true
  Ranged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon takes their held item, uses it as a weapon and the referee\
  \ is somehow OK with this. The held item remains in the field and may be recovered\
  \ after the battle."
Effect: Single Target. Ranged. *If the User is holding an Item, Add up to 4 dice to
  the damage pool. User loses its Held Item. See p. 530
Name: Fling
Power: 1
Target: Foe
Type: Dark
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