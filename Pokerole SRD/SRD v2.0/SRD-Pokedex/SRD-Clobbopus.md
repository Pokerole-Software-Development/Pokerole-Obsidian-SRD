---
Ability1: Limber
Ability2: ''
BookSprite: SRD-clobbopus-BookSprite.png
BoxSprite: SRD-clobbopus-BoxSprite.png
DexCategory: Tantrum Pokemon
DexDescription: "It\u2019s very curious and child-like, but it investigates things\
  \ by try to punch them with its tentacles, despite this, the tentacles tear off\
  \ easily, but don\u2019t be alarmed for they\u2019ll regrow in a few days."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Grapploct]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Technician
HomeSprite: SRD-clobbopus-HomeSprite.png
Image: clobbopus.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Rock Smash|Rock Smash]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Feint|Feint]]'
- - Beginner
  - '[[SRD-Bind|Bind]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Detect|Detect]]'
- - Amateur
  - '[[SRD-Brick Break|Brick Break]]'
- - Amateur
  - '[[SRD-Bulk Up|Bulk Up]]'
- - Amateur
  - '[[SRD-Submission|Submission]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Reversal|Reversal]]'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Soak|Soak]]'
- - Pro
  - '[[SRD-Circle Throw|Circle Throw]]'
- - Pro
  - '[[SRD-Seismic Toss|Seismic Toss]]'
Number: 852
ShuffleToken: SRD-clobbopus-ShuffleToken.png
Type1: Fighting
Type2: ''
Weight:
  Kilograms: 4.0
  Pounds: 8.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-clobbopus-BookSprite.png|wsmall]]
> ![[SRD-clobbopus-HomeSprite.png]]
> ![[SRD-clobbopus-BoxSprite.png|htiny]]
> ![[SRD-clobbopus-ShuffleToken.png|wsmall]]


*Tantrum Pokemon*
*It’s very curious and child-like, but it investigates things by try to punch them with its tentacles, despite this, the tentacles tear off easily, but don’t be alarmed for they’ll regrow in a few days.*

**DexID**:: 0852
**Name**:: Clobbopus
**Type**:: Fighting
**Abilities**:: [[SRD-Limber|Limber]] ([[SRD-Technician|Technician]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 8.8lbs / 4.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Grapploct]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Clobbopus.md"
flatten moves as T
where file.path = this.file.path
```
