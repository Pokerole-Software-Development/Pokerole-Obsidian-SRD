---
Ability1: Overgrow
Ability2: ''
BoxSprite: SRD-BoxSprite-bulbasaur.png
EventAbilities: ''
GenderType: ''
HasForm: 'No'
HiddenAbility: Chlorophyll
HomeSprite: SRD-HomeSprite-bulbasaur.png
Learnset: '[[SRD-Bulbasaur-Learnset]]'
Legendary: 'No'
Name: Bulbasaur
Number: 1
Sprite: bulbasaur.png
Type1: Grass
Type2: Poison
---

#PokeroleSRD/Pokedex

# `= this.name`

![[SRD-HomeSprite-bulbasaur.png|right]]

**DexID**:: 0001
**Species**:: Bulbasaur
**Type**:: Grass / Poison
**Abilities**:: [[SRD-Overgrow|Overgrow]] ([[SRD-Chlorophyll|Chlorophyll]])
**Base HP**:: 3

![[SRD-BoxSprite-bulbasaur.png|right]]

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Recommended Rank**:: Beginner
**Good Starter**:: Yes
**Can Evolve**:: Yes

![[SRD-Bulbasaur-Learnset]]