---
Ability1: Steam Engine
Ability2: Heatproof
BookSprite: SRD-rolycoly-BookSprite.png
BoxSprite: SRD-rolycoly-BoxSprite.png
DexCategory: Coal Pokemon
DexDescription: "This Pokemon was discovered inside a coal mine. It looks like a clump\
  \ of coal only it moves like a unicycle. When it gets angry it glows burning hot\
  \ but when it\u2019s happy it lets out soft crackles and keeps a steady warmth."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Carkol]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Flash Fire
HomeSprite: SRD-rolycoly-HomeSprite.png
Image: rolycoly.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Smokescreen|Smokescreen]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Beginner
  - '[[SRD-Smack Down|Smack Down]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Rock Polish|Rock Polish]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Incinerate|Incinerate]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Ace
  - '[[SRD-Heat Crash|Heat Crash]]'
- - Ace
  - '[[SRD-Rock Blast|Rock Blast]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Endure|Endure]]'
- - Pro
  - '[[SRD-Spikes|Spikes]]'
- - Pro
  - '[[SRD-Substitute|Substitute]]'
Number: 837
ShuffleToken: SRD-rolycoly-ShuffleToken.png
Type1: Rock
Type2: ''
Weight:
  Kilograms: 12.0
  Pounds: 26.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-rolycoly-BookSprite.png|wsmall]]
> ![[SRD-rolycoly-HomeSprite.png]]
> ![[SRD-rolycoly-BoxSprite.png|htiny]]
> ![[SRD-rolycoly-ShuffleToken.png|wsmall]]


*Coal Pokemon*
*This Pokemon was discovered inside a coal mine. It looks like a clump of coal only it moves like a unicycle. When it gets angry it glows burning hot but when it’s happy it lets out soft crackles and keeps a steady warmth.*

**DexID**:: 0837
**Name**:: Rolycoly
**Type**:: Rock
**Abilities**:: [[SRD-Steam Engine|Steam Engine]] / [[SRD-Heatproof|Heatproof]] ([[SRD-Flash Fire|Flash Fire]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'0" / 0.3m
**Weight**: 26.5lbs / 12.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| To        | [[SRD-Carkol]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Rolycoly.md"
flatten moves as T
where file.path = this.file.path
```
