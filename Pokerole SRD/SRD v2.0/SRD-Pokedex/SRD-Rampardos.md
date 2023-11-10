---
Ability1: Mold Breaker
Ability2: ''
BookSprite: SRD-rampardos-BookSprite.png
BoxSprite: SRD-rampardos-BoxSprite.png
DexCategory: Head Butt Pokemon
DexDescription: Its skull withstands any magnitude of impact. As a result, its brain
  never gets the chance to grow, this may have been the cause of its extinction. It
  is capable of rolling a truck over with a single strike.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Cranidos]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: Sheer Force
HomeSprite: SRD-rampardos-HomeSprite.png
Image: rampardos.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Take Down|Take Down]]'
- - Beginner
  - '[[SRD-Pursuit|Pursuit]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Assurance|Assurance]]'
- - Amateur
  - '[[SRD-Chip Away|Chip Away]]'
- - Amateur
  - '[[SRD-Endeavor|Endeavor]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Ace
  - '[[SRD-Screech|Screech]]'
- - Ace
  - '[[SRD-Head Smash|Head Smash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Superpower|Superpower]]'
- - Pro
  - '[[SRD-Iron Head|Iron Head]]'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
Number: 409
ShuffleToken: SRD-rampardos-ShuffleToken.png
Type1: Rock
Type2: ''
Weight:
  Kilograms: 102.5
  Pounds: 226.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-rampardos-BookSprite.png|wsmall]]
> ![[SRD-rampardos-HomeSprite.png]]
> ![[SRD-rampardos-BoxSprite.png|htiny]]
> ![[SRD-rampardos-ShuffleToken.png|wsmall]]


*Head Butt Pokemon*
*Its skull withstands any magnitude of impact. As a result, its brain never gets the chance to grow, this may have been the cause of its extinction. It is capable of rolling a truck over with a single strike.*

**DexID**:: 0409
**Name**:: Rampardos
**Type**:: Rock
**Abilities**:: [[SRD-Mold Breaker|Mold Breaker]] ([[SRD-Sheer Force|Sheer Force]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::4)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 5'2" / 1.6m
**Weight**: 226.0lbs / 102.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Cranidos]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Rampardos.md"
flatten moves as T
where file.path = this.file.path
```
