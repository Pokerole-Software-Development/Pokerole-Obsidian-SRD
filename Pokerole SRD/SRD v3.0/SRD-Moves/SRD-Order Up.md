---
Accuracy1: Insight
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  Unique: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user waits for orders and adheres to the strategy of a smaller but
  smarter ally.
Effect: 'Single Target. Unique. If the User is giving cover to a #978 Tatsugiri Ally.
  Increase by 1 an Attribute depending on the Ally''s color. *Orange - Strength *Red
  - Defense *Yellow - Dexterity'
Name: Order Up
Power: 3
Target: Foe
Type: Dragon
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