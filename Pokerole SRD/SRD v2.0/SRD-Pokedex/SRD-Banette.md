---
Ability1: Insomnia
Ability2: Frisk
BookSprite: SRD-banette-BookSprite.png
BoxSprite: SRD-banette-BoxSprite.png
DexCategory: Marionette Pokemon
DexDescription: "It\u2019s body is usually a discarded doll or toy. Its spirit is\
  \ made of dark feelings and is overrun by the desire of revenge towards the kid\
  \ that threw the toy away. If you open its mouth, all the cursed energy will escape."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Shuppet]]'
  Speed: Medium
- Evolves: To
  Item: Banettite
  Kind: Mega
  Pokemon: '[[SRD-Banette (Mega Form)]]'
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Cursed Body
HomeSprite: SRD-banette-HomeSprite.png
Image: banette.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Knock Off|Knock Off]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Spite|Spite]]'
- - Beginner
  - '[[SRD-Night Shade|Night Shade]]'
- - Beginner
  - '[[SRD-Screech|Screech]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Will-O-Wisp|Will-O-Wisp]]'
- - Amateur
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Hex|Hex]]'
- - Amateur
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - Amateur
  - '[[SRD-Snatch|Snatch]]'
- - Amateur
  - '[[SRD-Embargo|Embargo]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Ace
  - '[[SRD-Grudge|Grudge]]'
- - Ace
  - '[[SRD-Trick|Trick]]'
- - Ace
  - '[[SRD-Phantom Force|Phantom Force]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Role Play|Role Play]]'
- - Pro
  - '[[SRD-Destiny Bond|Destiny Bond]]'
- - Pro
  - '[[SRD-Icy Wind|Icy Wind]]'
Number: 354
ShuffleToken: SRD-banette-ShuffleToken.png
Type1: Ghost
Type2: ''
Weight:
  Kilograms: 12.5
  Pounds: 27.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-banette-BookSprite.png|wsmall]]
> ![[SRD-banette-HomeSprite.png]]
> ![[SRD-banette-BoxSprite.png|htiny]]
> ![[SRD-banette-ShuffleToken.png|wsmall]]


*Marionette Pokemon*
*It’s body is usually a discarded doll or toy. Its spirit is made of dark feelings and is overrun by the desire of revenge towards the kid that threw the toy away. If you open its mouth, all the cursed energy will escape.*

**DexID**:: 0354
**Name**:: Banette
**Type**:: Ghost
**Abilities**:: [[SRD-Insomnia|Insomnia]] / [[SRD-Frisk|Frisk]] ([[SRD-Cursed Body|Cursed Body]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'6" / 1.1m
**Weight**: 27.6lbs / 12.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                     | Kind   | Speed   | Item      |
|:----------|:----------------------------|:-------|:--------|:----------|
| From      | [[SRD-Shuppet]]             | Level  | Medium  |           |
| To        | [[SRD-Banette (Mega Form)]] | Mega   |         | Banettite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Banette.md"
flatten moves as T
where file.path = this.file.path
```
