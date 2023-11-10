---
Ability1: Compound Eyes
Ability2: Unnerve
BookSprite: SRD-galvantula-BookSprite.png
BoxSprite: SRD-galvantula-BoxSprite.png
DexCategory: EleSpider Pokemon
DexDescription: They employ an electrically charged web to trap their prey. While
  it is immobilized by shock, they leisurely consume it. They usually live alone but
  there have been cases of large swarms living together in caves.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Joltik]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Swarm
HomeSprite: SRD-galvantula-HomeSprite.png
Image: galvantula.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Absorb|Absorb]]'
- - Starter
  - '[[SRD-String Shot|String Shot]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Beginner
  - '[[SRD-Spider Web|Spider Web]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sticky Web|Sticky Web]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - Amateur
  - '[[SRD-Electroweb|Electroweb]]'
- - Amateur
  - '[[SRD-Bug Bite|Bug Bite]]'
- - Amateur
  - '[[SRD-Gastro Acid|Gastro Acid]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Electro Ball|Electro Ball]]'
- - Amateur
  - '[[SRD-Signal Beam|Signal Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Agility|Agility]]'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - Ace
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Cross Poison|Cross Poison]]'
- - Pro
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Pro
  - '[[SRD-Giga Drain|Giga Drain]]'
Number: 596
ShuffleToken: SRD-galvantula-ShuffleToken.png
Type1: Bug
Type2: Electric
Weight:
  Kilograms: 14.3
  Pounds: 31.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-galvantula-BookSprite.png|wsmall]]
> ![[SRD-galvantula-HomeSprite.png]]
> ![[SRD-galvantula-BoxSprite.png|htiny]]
> ![[SRD-galvantula-ShuffleToken.png|wsmall]]


*EleSpider Pokemon*
*They employ an electrically charged web to trap their prey. While it is immobilized by shock, they leisurely consume it. They usually live alone but there have been cases of large swarms living together in caves.*

**DexID**:: 0596
**Name**:: Galvantula
**Type**:: Bug / Electric
**Abilities**:: [[SRD-Compound Eyes|Compound Eyes]] / [[SRD-Unnerve|Unnerve]] ([[SRD-Swarm|Swarm]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'6" / 0.8m
**Weight**: 31.5lbs / 14.3kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Joltik]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Galvantula.md"
flatten moves as T
where file.path = this.file.path
```
