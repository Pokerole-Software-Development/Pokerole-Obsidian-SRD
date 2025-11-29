---
Accuracy1: Dexterity
Accuracy2: Stealth
AddedEffects: {}
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon is attracted to shiny and colorful items. They don\u2019\
  t understand when something is not theirs for the taking so they just take it when\
  \ no one is looking."
Effect: Single Target. The User steals the Target's Held Item. If the User already
  has a Held Item, this effect fails.
Name: Covet
Power: 2
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