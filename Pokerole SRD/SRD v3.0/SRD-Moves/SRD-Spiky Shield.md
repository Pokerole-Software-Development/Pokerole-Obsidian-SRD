---
Accuracy1: Vitality
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  IgnoreDefenses: true
  Reaction: '3'
  ShieldMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon bunkers themselves inside a shield of thorned brambles\
  \ sprouting from the ground. Anyone who gets too close will get tangled in the spiky\
  \ vines."
Effect: Target Self. Reaction 3. Shield Move. Reduce 3 Damage this Pokemon would receive
  from a Damaging Move. If the Foe used a non-ranged Physical Move. Roll 2 Dice of
  Typeless Damage against it, ignore defenses.
Name: Spiky Shield
Power: 0
Target: Self
Type: Grass
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