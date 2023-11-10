---
Ability1: Guts
Ability2: ''
BookSprite: SRD-larvitar-BookSprite.png
BoxSprite: SRD-larvitar-BoxSprite.png
DexCategory: Rock Skin Pokemon
DexDescription: "Born deep underground, they don\u2019t emerge until they\u2019ve\
  \ eaten a whole mountain of soil. Only the strongest and more ferocious ever come\
  \ out to roam about. They hate being disturbed."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Pupitar]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Sand Veil
HomeSprite: SRD-larvitar-HomeSprite.png
Image: larvitar.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Bite|Bite]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sandstorm|Sandstorm]]'
- - Beginner
  - '[[SRD-Screech|Screech]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Chip Away|Chip Away]]'
- - Amateur
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Thrash|Thrash]]'
- - Amateur
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - Amateur
  - '[[SRD-Payback|Payback]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Stone Edge|Stone Edge]]'
- - Ace
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Pro
  - '[[SRD-Spite|Spite]]'
- - Pro
  - '[[SRD-Focus Energy|Focus Energy]]'
Number: 246
ShuffleToken: SRD-larvitar-ShuffleToken.png
Type1: Rock
Type2: Ground
Weight:
  Kilograms: 72.0
  Pounds: 158.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-larvitar-BookSprite.png|wsmall]]
> ![[SRD-larvitar-HomeSprite.png]]
> ![[SRD-larvitar-BoxSprite.png|htiny]]
> ![[SRD-larvitar-ShuffleToken.png|wsmall]]


*Rock Skin Pokemon*
*Born deep underground, they don’t emerge until they’ve eaten a whole mountain of soil. Only the strongest and more ferocious ever come out to roam about. They hate being disturbed.*

**DexID**:: 0246
**Name**:: Larvitar
**Type**:: Rock / Ground
**Abilities**:: [[SRD-Guts|Guts]] ([[SRD-Sand Veil|Sand Veil]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 158.7lbs / 72.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Pupitar]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Larvitar.md"
flatten moves as T
where file.path = this.file.path
```
