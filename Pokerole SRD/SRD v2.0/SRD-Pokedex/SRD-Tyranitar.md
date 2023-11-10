---
Ability1: Sand Stream
Ability2: ''
BookSprite: SRD-tyranitar-BookSprite.png
BoxSprite: SRD-tyranitar-BoxSprite.png
DexCategory: Armor Pokemon
DexDescription: "Its body is hardly damaged by any attack, so it\u2019s always eager\
  \ to fight. They are extremely strong, their rage can change landscapes. Tyranitars\
  \ are insolents, rebels and they care about no one."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Pupitar]]'
  Speed: Slow
- Evolves: To
  Item: Tyranitarite
  Kind: Mega
  Pokemon: '[[SRD-Tyranitar (Mega Form)]]'
GenderType: ''
Height:
  Feet: 6.6
  Meters: 2.0
HiddenAbility: Unnerve
HomeSprite: SRD-tyranitar-HomeSprite.png
Image: tyranitar.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Bite|Bite]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Screech|Screech]]'
- - Beginner
  - '[[SRD-Sandstorm|Sandstorm]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Amateur
  - '[[SRD-Ice Fang|Ice Fang]]'
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
- - Ace
  - '[[SRD-Giga Impact|Giga Impact]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
- - Pro
  - '[[SRD-Superpower|Superpower]]'
Number: 248
ShuffleToken: SRD-tyranitar-ShuffleToken.png
Type1: Rock
Type2: Dark
Weight:
  Kilograms: 202.0
  Pounds: 445.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-tyranitar-BookSprite.png|wsmall]]
> ![[SRD-tyranitar-HomeSprite.png]]
> ![[SRD-tyranitar-BoxSprite.png|htiny]]
> ![[SRD-tyranitar-ShuffleToken.png|wsmall]]


*Armor Pokemon*
*Its body is hardly damaged by any attack, so it’s always eager to fight. They are extremely strong, their rage can change landscapes. Tyranitars are insolents, rebels and they care about no one.*

**DexID**:: 0248
**Name**:: Tyranitar
**Type**:: Rock / Dark
**Abilities**:: [[SRD-Sand Stream|Sand Stream]] ([[SRD-Unnerve|Unnerve]])
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 6'6" / 2.0m
**Weight**: 445.3lbs / 202.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon                       | Kind   | Speed   | Item         |
|:----------|:------------------------------|:-------|:--------|:-------------|
| From      | [[SRD-Pupitar]]               | Level  | Slow    |              |
| To        | [[SRD-Tyranitar (Mega Form)]] | Mega   |         | Tyranitarite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Tyranitar.md"
flatten moves as T
where file.path = this.file.path
```
