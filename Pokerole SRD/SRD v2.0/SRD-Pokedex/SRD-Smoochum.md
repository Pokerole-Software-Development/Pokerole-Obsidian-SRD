---
Ability1: Oblivious
Ability2: Forewarn
BookSprite: SRD-smoochum-BookSprite.png
BoxSprite: SRD-smoochum-BoxSprite.png
DexCategory: Kiss Pokemon
DexDescription: They examine their surroundings with their lips. They love to smooch,
  but Pokemon dislike their kisses. Smoochums are always running excitedly, but they
  are clumsy and end up stumbling and crying.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Jynx]]'
  Speed: Medium
GenderType: F
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Hydration
HomeSprite: SRD-smoochum-HomeSprite.png
Image: smoochum.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Lick|Lick]]'
- - Beginner
  - '[[SRD-Sweet Kiss|Sweet Kiss]]'
- - Beginner
  - '[[SRD-Powder Snow|Powder Snow]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Confusion|Confusion]]'
- - Amateur
  - '[[SRD-Sing|Sing]]'
- - Amateur
  - '[[SRD-Heart Stamp|Heart Stamp]]'
- - Amateur
  - '[[SRD-Mean Look|Mean Look]]'
- - Amateur
  - '[[SRD-Fake Tears|Fake Tears]]'
- - Amateur
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Amateur
  - '[[SRD-Avalanche|Avalanche]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Copycat|Copycat]]'
- - Ace
  - '[[SRD-Perish Song|Perish Song]]'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fake Out|Fake Out]]'
- - Pro
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Pro
  - '[[SRD-Magic Coat|Magic Coat]]'
Number: 238
ShuffleToken: SRD-smoochum-ShuffleToken.png
Type1: Ice
Type2: Psychic
Weight:
  Kilograms: 6.0
  Pounds: 13.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-smoochum-BookSprite.png|wsmall]]
> ![[SRD-smoochum-HomeSprite.png]]
> ![[SRD-smoochum-BoxSprite.png|htiny]]
> ![[SRD-smoochum-ShuffleToken.png|wsmall]]


*Kiss Pokemon*
*They examine their surroundings with their lips. They love to smooch, but Pokemon dislike their kisses. Smoochums are always running excitedly, but they are clumsy and end up stumbling and crying.*

**DexID**:: 0238
**Name**:: Smoochum
**Type**:: Ice / Psychic
**Abilities**:: [[SRD-Oblivious|Oblivious]] / [[SRD-Forewarn|Forewarn]] ([[SRD-Hydration|Hydration]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::2)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 13.2lbs / 6.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon      | Kind   | Speed   |
|:----------|:-------------|:-------|:--------|
| To        | [[SRD-Jynx]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Smoochum.md"
flatten moves as T
where file.path = this.file.path
```
