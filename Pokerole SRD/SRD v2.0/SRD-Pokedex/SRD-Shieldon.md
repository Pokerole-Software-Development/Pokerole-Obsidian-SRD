---
Ability1: Sturdy
Ability2: ''
BookSprite: SRD-shieldon-BookSprite.png
BoxSprite: SRD-shieldon-BoxSprite.png
DexCategory: Shield Pokemon
DexDescription: It was cloned from a fossil dug out from a layer of clay. It is outstandingly
  armored. As a result, it can eat grass and berries without having to fight many
  Pokemon who would dare to prey on it.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Bastiodon]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Soundproof
HomeSprite: SRD-shieldon-HomeSprite.png
Image: shieldon.png
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
  - '[[SRD-Counter|Counter]]'
Number: 410
ShuffleToken: SRD-shieldon-ShuffleToken.png
Type1: Rock
Type2: Steel
Weight:
  Kilograms: 57.0
  Pounds: 125.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-shieldon-BookSprite.png|wsmall]]
> ![[SRD-shieldon-HomeSprite.png]]
> ![[SRD-shieldon-BoxSprite.png|htiny]]
> ![[SRD-shieldon-ShuffleToken.png|wsmall]]


*Shield Pokemon*
*It was cloned from a fossil dug out from a layer of clay. It is outstandingly armored. As a result, it can eat grass and berries without having to fight many Pokemon who would dare to prey on it.*

**DexID**:: 0410
**Name**:: Shieldon
**Type**:: Rock / Steel
**Abilities**:: [[SRD-Sturdy|Sturdy]] ([[SRD-Soundproof|Soundproof]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 1'6" / 0.5m
**Weight**: 125.7lbs / 57.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Bastiodon]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Shieldon.md"
flatten moves as T
where file.path = this.file.path
```
