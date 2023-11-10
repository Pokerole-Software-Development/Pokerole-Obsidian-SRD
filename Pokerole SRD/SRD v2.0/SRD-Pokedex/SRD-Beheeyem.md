---
Ability1: Telepathy
Ability2: Synchronize
BookSprite: SRD-beheeyem-BookSprite.png
BoxSprite: SRD-beheeyem-BoxSprite.png
DexCategory: Cerebral Pokemon
DexDescription: "Apparently, it communicates by flashing its three fingers, but the\
  \ patterns haven\u2019t been decoded. It uses psychic power to control an opponent\u2019\
  s brain and tampers with its memories and personality."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Elgyem]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Analytic
HomeSprite: SRD-beheeyem-HomeSprite.png
Image: beheeyem.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Confusion|Confusion]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Heal Block|Heal Block]]'
- - Beginner
  - '[[SRD-Miracle Eye|Miracle Eye]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Psychic Terrain|Psychic Terrain]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Imprison|Imprison]]'
- - Amateur
  - '[[SRD-Hidden Power|Hidden Power]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Amateur
  - '[[SRD-Simple Beam|Simple Beam]]'
- - Amateur
  - '[[SRD-Recover|Recover]]'
- - Amateur
  - '[[SRD-Psych Up|Psych Up]]'
- - Amateur
  - '[[SRD-Wonder Room|Wonder Room]]'
- - Amateur
  - '[[SRD-Calm Mind|Calm Mind]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Guard Split|Guard Split]]'
- - Ace
  - '[[SRD-Power Split|Power Split]]'
- - Ace
  - '[[SRD-Synchronoise|Synchronoise]]'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Cosmic Power|Cosmic Power]]'
- - Pro
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Pro
  - '[[SRD-Teleport|Teleport]]'
Number: 606
ShuffleToken: SRD-beheeyem-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 34.5
  Pounds: 76.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-beheeyem-BookSprite.png|wsmall]]
> ![[SRD-beheeyem-HomeSprite.png]]
> ![[SRD-beheeyem-BoxSprite.png|htiny]]
> ![[SRD-beheeyem-ShuffleToken.png|wsmall]]


*Cerebral Pokemon*
*Apparently, it communicates by flashing its three fingers, but the patterns haven’t been decoded. It uses psychic power to control an opponent’s brain and tampers with its memories and personality.*

**DexID**:: 0606
**Name**:: Beheeyem
**Type**:: Psychic
**Abilities**:: [[SRD-Telepathy|Telepathy]] / [[SRD-Synchronize|Synchronize]] ([[SRD-Analytic|Analytic]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 3'3" / 1.0m
**Weight**: 76.1lbs / 34.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Elgyem]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Beheeyem.md"
flatten moves as T
where file.path = this.file.path
```
