---
Ability1: Fluffy
Ability2: Run Away
BookSprite: SRD-wooloo-BookSprite.png
BoxSprite: SRD-wooloo-BoxSprite.png
DexCategory: Sheep Pokemon
DexDescription: Woolo's wool is incredibly resilient, it serves as a cushion when
  they fall from high mountain cliffs. They need to be sheared or their wool will
  be too heavy to move. A sweater made with this wool will last for a lifetime.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Dubwool]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Bulletproof
HomeSprite: SRD-wooloo-HomeSprite.png
Image: wooloo.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Beginner
  - '[[SRD-Copycat|Copycat]]'
- - '---------------------------'
  - '---------------------------'
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
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Substitute|Substitute]]'
- - Pro
  - '[[SRD-Rest|Rest]]'
- - Pro
  - '[[SRD-Sleep Talk|Sleep Talk]]'
Number: 831
ShuffleToken: SRD-wooloo-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 6.0
  Pounds: 13.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-wooloo-BookSprite.png|wsmall]]
> ![[SRD-wooloo-HomeSprite.png]]
> ![[SRD-wooloo-BoxSprite.png|htiny]]
> ![[SRD-wooloo-ShuffleToken.png|wsmall]]


*Sheep Pokemon*
*Woolo's wool is incredibly resilient, it serves as a cushion when they fall from high mountain cliffs. They need to be sheared or their wool will be too heavy to move. A sweater made with this wool will last for a lifetime.*

**DexID**:: 0831
**Name**:: Wooloo
**Type**:: Normal
**Abilities**:: [[SRD-Fluffy|Fluffy]] / [[SRD-Run Away|Run Away]] ([[SRD-Bulletproof|Bulletproof]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 13.2lbs / 6.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Dubwool]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Wooloo.md"
flatten moves as T
where file.path = this.file.path
```
