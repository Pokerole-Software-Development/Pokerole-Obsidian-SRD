---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-haunter-BookSprite.png
BoxSprite: SRD-haunter-BoxSprite.png
DexCategory: Gas Pokemon
DexDescription: Haunter is a dangerous Pokemon. it will try to lick you with its tongue
  to steal your life away. If you get the feeling of being watched in darkness when
  nobody is around, it means a Haunter is there.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Gastly]]'
  Speed: Medium
- Evolves: To
  Kind: Trade
  Pokemon: '[[SRD-Gengar]]'
GenderType: ''
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: ''
HomeSprite: SRD-haunter-HomeSprite.png
Image: haunter.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Spite|Spite]]'
- - Starter
  - '[[SRD-Lick|Lick]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Curse|Curse]]'
- - Beginner
  - '[[SRD-Mean Look|Mean Look]]'
- - Beginner
  - '[[SRD-Night Shade|Night Shade]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Amateur
  - '[[SRD-Shadow Punch|Shadow Punch]]'
- - Amateur
  - '[[SRD-Payback|Payback]]'
- - Amateur
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - Amateur
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Dream Eater|Dream Eater]]'
- - Ace
  - '[[SRD-Destiny Bond|Destiny Bond]]'
- - Ace
  - '[[SRD-Hex|Hex]]'
- - Ace
  - '[[SRD-Nightmare|Nightmare]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Pro
  - '[[SRD-Grudge|Grudge]]'
- - Pro
  - '[[SRD-Trick|Trick]]'
Number: 93
ShuffleToken: SRD-haunter-ShuffleToken.png
Type1: Ghost
Type2: Poison
Weight:
  Kilograms: 0.1
  Pounds: 0.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-haunter-BookSprite.png|wsmall]]
> ![[SRD-haunter-HomeSprite.png]]
> ![[SRD-haunter-BoxSprite.png|htiny]]
> ![[SRD-haunter-ShuffleToken.png|wsmall]]


*Gas Pokemon*
*Haunter is a dangerous Pokemon. it will try to lick you with its tongue to steal your life away. If you get the feeling of being watched in darkness when nobody is around, it means a Haunter is there.*

**DexID**:: 0093
**Name**:: Haunter
**Type**:: Ghost / Poison
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 5'2" / 1.6m
**Weight**: 0.2lbs / 0.1kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Gastly]] | Level  | Medium  |
| To        | [[SRD-Gengar]] | Trade  |         |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Haunter.md"
flatten moves as T
where file.path = this.file.path
```
