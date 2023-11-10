---
Ability1: Fluffy
Ability2: Steadfast
BookSprite: SRD-dubwool-BookSprite.png
BoxSprite: SRD-dubwool-BoxSprite.png
DexCategory: Sheep Pokemon
DexDescription: Humble and calm, their wool has springy properties. A king in ancient
  times ordered a carpet made from 100 Dubwool, when it was done, those who step on
  it started to bounce the moment they set foot on it.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Wooloo]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: Bulletproof
HomeSprite: SRD-dubwool-HomeSprite.png
Image: dubwool.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-Defense Curl|Defense Curl]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Copycat|Copycat]]'
- - Amateur
  - '[[SRD-Guard Split|Guard Split]]'
- - Amateur
  - '[[SRD-Double Kick|Double Kick]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Guard Swap|Guard Swap]]'
- - Ace
  - '[[SRD-Reversal|Reversal]]'
- - Ace
  - '[[SRD-Cotton Guard|Cotton Guard]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Last Resort|Last Resort]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Bounce|Bounce]]'
- - Pro
  - '[[SRD-Agility|Agility]]'
- - Pro
  - '[[SRD-Protect|Protect]]'
Number: 832
ShuffleToken: SRD-dubwool-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 43.0
  Pounds: 94.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-dubwool-BookSprite.png|wsmall]]
> ![[SRD-dubwool-HomeSprite.png]]
> ![[SRD-dubwool-BoxSprite.png|htiny]]
> ![[SRD-dubwool-ShuffleToken.png|wsmall]]


*Sheep Pokemon*
*Humble and calm, their wool has springy properties. A king in ancient times ordered a carpet made from 100 Dubwool, when it was done, those who step on it started to bounce the moment they set foot on it.*

**DexID**:: 0832
**Name**:: Dubwool
**Type**:: Normal
**Abilities**:: [[SRD-Fluffy|Fluffy]] / [[SRD-Steadfast|Steadfast]] ([[SRD-Bulletproof|Bulletproof]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'3" / 1.3m
**Weight**: 94.8lbs / 43.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Wooloo]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Dubwool.md"
flatten moves as T
where file.path = this.file.path
```
