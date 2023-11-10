---
Ability1: Prankster
Ability2: Frisk
BookSprite: SRD-grimmsnarl-BookSprite.png
BoxSprite: SRD-grimmsnarl-BoxSprite.png
DexCategory: Bulk Up Pokemon
DexDescription: Its hairs work like muscle fibers. When its hairs unfurl, they latch
  on to opponents, ensnaring them as tentacles would. They often make others trip
  or get them hanging upside down to amuse themselves.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Morgrem]]'
  Speed: Medium
GenderType: M
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Pickpocket
HomeSprite: SRD-grimmsnarl-HomeSprite.png
Image: grimmsnarl.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Fake Out|Fake Out]]'
- - Starter
  - '[[SRD-Confide|Confide]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Flatter|Flatter]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fake Tears|Fake Tears]]'
- - Amateur
  - '[[SRD-Assurance|Assurance]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Amateur
  - '[[SRD-Torment|Torment]]'
- - Amateur
  - '[[SRD-Spirit Break|Spirit Break]]'
- - Amateur
  - '[[SRD-Power-Up Punch|Power-Up Punch]]'
- - Amateur
  - '[[SRD-Bulk Up|Bulk Up]]'
- - Amateur
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - Amateur
  - '[[SRD-False Surrender|False Surrender]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Foul Play|Foul Play]]'
- - Ace
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Ace
  - '[[SRD-Play Rough|Play Rough]]'
- - Ace
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Draining Kiss|Draining Kiss]]'
- - Pro
  - '[[SRD-Protect|Protect]]'
- - Pro
  - '[[SRD-Reflect|Reflect]]'
Number: 861
ShuffleToken: SRD-grimmsnarl-ShuffleToken.png
Type1: Dark
Type2: Fairy
Weight:
  Kilograms: 61.0
  Pounds: 134.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-grimmsnarl-BookSprite.png|wsmall]]
> ![[SRD-grimmsnarl-HomeSprite.png]]
> ![[SRD-grimmsnarl-BoxSprite.png|htiny]]
> ![[SRD-grimmsnarl-ShuffleToken.png|wsmall]]


*Bulk Up Pokemon*
*Its hairs work like muscle fibers. When its hairs unfurl, they latch on to opponents, ensnaring them as tentacles would. They often make others trip or get them hanging upside down to amuse themselves.*

**DexID**:: 0861
**Name**:: Grimmsnarl
**Type**:: Dark / Fairy
**Abilities**:: [[SRD-Prankster|Prankster]] / [[SRD-Frisk|Frisk]] ([[SRD-Pickpocket|Pickpocket]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'9" / 1.5m
**Weight**: 134.5lbs / 61.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Morgrem]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Grimmsnarl.md"
flatten moves as T
where file.path = this.file.path
```
