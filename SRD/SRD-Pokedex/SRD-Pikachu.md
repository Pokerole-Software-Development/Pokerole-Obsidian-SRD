---
Ability1: Static
Ability2: ''
BoxSprite: SRD-BoxSprite-pikachu.png
EventAbilities: ''
GenderType: ''
HasForm: 'No'
HiddenAbility: Lightning Rod
HomeSprite: SRD-HomeSprite-pikachu.png
Learnset: '[[SRD-Pikachu-Learnset]]'
Legendary: 'No'
Name: Pikachu
Number: 25
Sprite: pikachu.png
Type1: Electric
Type2: ''
---

#PokeroleSRD/Pokedex

# `= this.name`

![[SRD-HomeSprite-pikachu.png|right]]

**DexID**:: 0025
**Species**:: Pikachu
**Type**:: Electric
**Abilities**:: [[SRD-Static|Static]] ([[SRD-Lightning Rod|Lightning Rod]])
**Base HP**:: 4

![[SRD-BoxSprite-pikachu.png|right]]

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Recommended Rank**:: Beginner
**Good Starter**:: Yes
**Can Evolve**:: Yes

![[SRD-Pikachu-Learnset]]