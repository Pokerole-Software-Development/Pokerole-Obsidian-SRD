---
Ability1: Sturdy
Ability2: ''
BookSprite: SRD-bastiodon-BookSprite.png
BoxSprite: SRD-bastiodon-BoxSprite.png
DexCategory: Shield Pokemon
DexDescription: They lived in herds, millions of years ago. They would line together
  to shield their young. Despite its rough and scary exterior, this Pokemon is calm,
  gentle natured and a strict herbivore.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Shieldon]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: Soundproof
HomeSprite: SRD-bastiodon-HomeSprite.png
Image: bastiodon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Protect|Protect]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Taunt|Taunt]]'
- - Beginner
  - '[[SRD-Metal Sound|Metal Sound]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Block|Block]]'
- - Amateur
  - '[[SRD-Endure|Endure]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Metal Burst|Metal Burst]]'
- - Ace
  - '[[SRD-Iron Head|Iron Head]]'
- - Ace
  - '[[SRD-Heavy Slam|Heavy Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Guard Split|Guard Split]]'
- - Pro
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Pro
  - '[[SRD-Fissure|Fissure]]'
Number: 411
ShuffleToken: SRD-bastiodon-ShuffleToken.png
Type1: Rock
Type2: Steel
Weight:
  Kilograms: 149.5
  Pounds: 329.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-bastiodon-BookSprite.png|wsmall]]
> ![[SRD-bastiodon-HomeSprite.png]]
> ![[SRD-bastiodon-BoxSprite.png|htiny]]
> ![[SRD-bastiodon-ShuffleToken.png|wsmall]]


*Shield Pokemon*
*They lived in herds, millions of years ago. They would line together to shield their young. Despite its rough and scary exterior, this Pokemon is calm, gentle natured and a strict herbivore.*

**DexID**:: 0411
**Name**:: Bastiodon
**Type**:: Rock / Steel
**Abilities**:: [[SRD-Sturdy|Sturdy]] ([[SRD-Soundproof|Soundproof]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::4)/(MaxVitality::8)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::7)     |

**Height**: 4'3" / 1.3m
**Weight**: 329.6lbs / 149.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Shieldon]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Bastiodon.md"
flatten moves as T
where file.path = this.file.path
```
