---
Ability1: Overgrow
Ability2: ''
BoxSprite: SRD-BoxSprite-venusaur.png
EventAbilities: ''
GenderType: ''
HasAForm?: 'Yes'
HiddenAbility: Chlorophyll
HomeSprite: SRD-HomeSprite-venusaur.png
Learnset: '[[SRD-Venusaur-Learnset]]'
Legendary: 'No'
Name: Venusaur
Number: 3
Sprite: venusaur.png
Type1: Grass
Type2: Poison
---

#PokeroleSRD/Pokedex

# `= this.name`

![[SRD-HomeSprite-venusaur.png|right]]

**DexID**:: 0003
**Species**:: Venusaur
**Type**:: Grass / Poison
**Abilities**:: [[SRD-Overgrow|Overgrow]] ([[SRD-Chlorophyll|Chlorophyll]])
**Base HP**:: 5

![[SRD-BoxSprite-venusaur.png|right]]

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Recommended Rank**:: Ace
**Good Starter**:: No
**Can Evolve**:: No

![[SRD-Venusaur-Learnset]]