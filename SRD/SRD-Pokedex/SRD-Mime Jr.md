---
Ability1: Soundproof
Ability2: Filter
BookSprite: SRD-mime-jr-BookSprite.png
BoxSprite: SRD-mime-jr-BoxSprite.png
DexCategory: Mime Pokemon
DexDescription: "It likes places where people gather and imitates their expressions\
  \ to try to understand their feelings. It mimics foes, confuses them, then it escapes.\
  \ It doesn\u2019t take long to become a master mime."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Move: Mimic
  Pokemon: '[[SRD-Mr. Mime]]'
- Evolves: To
  Kind: Level
  Move: Mimic
  Pokemon: '[[SRD-Mr. Mime (Galarian Form)]]'
  Region: Galar
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Technician
HomeSprite: SRD-mime-jr-HomeSprite.png
Image: mime-jr.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tickle|Tickle]]'
- - Starter
  - '[[SRD-Barrier|Barrier]]'
- - Starter
  - '[[SRD-Confusion|Confusion]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Copycat|Copycat]]'
- - Beginner
  - '[[SRD-Meditate|Meditate]]'
- - Beginner
  - '[[SRD-Double Slap|Double Slap]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Mimic|Mimic]]'
- - Amateur
  - '[[SRD-Encore|Encore]]'
- - Amateur
  - '[[SRD-Light Screen|Light Screen]]'
- - Amateur
  - '[[SRD-Reflect|Reflect]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Substitute|Substitute]]'
- - Amateur
  - '[[SRD-Trick|Trick]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Recycle|Recycle]]'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Role Play|Role Play]]'
- - Ace
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Ace
  - '[[SRD-Safeguard|Safeguard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Teeter Dance|Teeter Dance]]'
- - Pro
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Pro
  - '[[SRD-Wake-Up Slap|Wake-Up Slap]]'
Number: 439
ShuffleToken: SRD-mime-jr-ShuffleToken.png
Type1: Psychic
Type2: Fairy
Weight:
  Kilograms: 13.0
  Pounds: 28.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-mime-jr-BookSprite.png|wsmall]]
> ![[SRD-mime-jr-HomeSprite.png]]
> ![[SRD-mime-jr-BoxSprite.png|htiny]]
> ![[SRD-mime-jr-ShuffleToken.png|wsmall]]


*Mime Pokemon*
*It likes places where people gather and imitates their expressions to try to understand their feelings. It mimics foes, confuses them, then it escapes. It doesn’t take long to become a master mime.*

**DexID**:: 0439
**Name**:: Mime Jr
**Type**:: Psychic / Fairy
**Abilities**:: [[SRD-Soundproof|Soundproof]] / [[SRD-Filter|Filter]] ([[SRD-Technician|Technician]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'0" / 0.6m
**Weight**: 28.7lbs / 13.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon                          | Kind   | Move   | Region   |
|:----------|:---------------------------------|:-------|:-------|:---------|
| To        | [[SRD-Mr. Mime]]                 | Level  | Mimic  |          |
| To        | [[SRD-Mr. Mime (Galarian Form)]] | Level  | Mimic  | Galar    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Mime Jr.md"
flatten moves as T
where file.path = this.file.path
```
