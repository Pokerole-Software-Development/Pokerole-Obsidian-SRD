---
Ability1: Blaze
Ability2: ''
BookSprite: SRD-infernape-BookSprite.png
BoxSprite: SRD-infernape-BoxSprite.png
DexCategory: Flame Pokemon
DexDescription: "Its fire crown showcases its proud and fiery nature. Infernape won\u2019\
  t hesitate to fight bigger foes and will take on any challenge they face. Once Infernape\
  \ enters a battle, it won\u2019t back down until it wins."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Monferno]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Iron Fist
HomeSprite: SRD-infernape-HomeSprite.png
Image: infernape.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Taunt|Taunt]]'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Mach Punch|Mach Punch]]'
- - Amateur
  - '[[SRD-Feint|Feint]]'
- - Amateur
  - '[[SRD-Flame Wheel|Flame Wheel]]'
- - Amateur
  - '[[SRD-Fire Spin|Fire Spin]]'
- - Amateur
  - '[[SRD-Punishment|Punishment]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Close Combat|Close Combat]]'
- - Ace
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - Ace
  - '[[SRD-Acrobatics|Acrobatics]]'
- - Ace
  - '[[SRD-Calm Mind|Calm Mind]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Endure|Endure]]'
- - Pro
  - '[[SRD-Dual Chop|Dual Chop]]'
- - Pro
  - '[[SRD-Blast Burn|Blast Burn]]'
Number: 392
ShuffleToken: SRD-infernape-ShuffleToken.png
Type1: Fire
Type2: Fighting
Weight:
  Kilograms: 55.0
  Pounds: 121.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-infernape-BookSprite.png|wsmall]]
> ![[SRD-infernape-HomeSprite.png]]
> ![[SRD-infernape-BoxSprite.png|htiny]]
> ![[SRD-infernape-ShuffleToken.png|wsmall]]


*Flame Pokemon*
*Its fire crown showcases its proud and fiery nature. Infernape won’t hesitate to fight bigger foes and will take on any challenge they face. Once Infernape enters a battle, it won’t back down until it wins.*

**DexID**:: 0392
**Name**:: Infernape
**Type**:: Fire / Fighting
**Abilities**:: [[SRD-Blaze|Blaze]] ([[SRD-Iron Fist|Iron Fist]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'9" / 1.2m
**Weight**: 121.3lbs / 55.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Monferno]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Infernape.md"
flatten moves as T
where file.path = this.file.path
```
