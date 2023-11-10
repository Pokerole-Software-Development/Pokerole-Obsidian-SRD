---
Ability1: Contrary
Ability2: Suction Cups
BookSprite: SRD-malamar-BookSprite.png
BoxSprite: SRD-malamar-BoxSprite.png
DexCategory: Overturning Pokemon
DexDescription: It lures prey close with hypnotic motions, then wraps its tentacles
  around it before finishing it off to eat it. This Pokemon are difficult to handle
  as they use their psychic abilities to do evil.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Inkay]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Infiltrator
HomeSprite: SRD-malamar-HomeSprite.png
Image: malamar.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Constrict|Constrict]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Peck|Peck]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Foul Play|Foul Play]]'
- - Beginner
  - '[[SRD-Reflect|Reflect]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Reversal|Reversal]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Psywave|Psywave]]'
- - Amateur
  - '[[SRD-Topsy-Turvy|Topsy-Turvy]]'
- - Amateur
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Switcheroo|Switcheroo]]'
- - Amateur
  - '[[SRD-Payback|Payback]]'
- - Amateur
  - '[[SRD-Pluck|Pluck]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Light Screen|Light Screen]]'
- - Ace
  - '[[SRD-Psycho Cut|Psycho Cut]]'
- - Ace
  - '[[SRD-Slash|Slash]]'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Power Split|Power Split]]'
- - Pro
  - '[[SRD-Knock Off|Knock Off]]'
- - Pro
  - '[[SRD-Simple Beam|Simple Beam]]'
Number: 687
ShuffleToken: SRD-malamar-ShuffleToken.png
Type1: Dark
Type2: Psychic
Weight:
  Kilograms: 47.0
  Pounds: 103.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-malamar-BookSprite.png|wsmall]]
> ![[SRD-malamar-HomeSprite.png]]
> ![[SRD-malamar-BoxSprite.png|htiny]]
> ![[SRD-malamar-ShuffleToken.png|wsmall]]


*Overturning Pokemon*
*It lures prey close with hypnotic motions, then wraps its tentacles around it before finishing it off to eat it. This Pokemon are difficult to handle as they use their psychic abilities to do evil.*

**DexID**:: 0687
**Name**:: Malamar
**Type**:: Dark / Psychic
**Abilities**:: [[SRD-Contrary|Contrary]] / [[SRD-Suction Cups|Suction Cups]] ([[SRD-Infiltrator|Infiltrator]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'9" / 1.5m
**Weight**: 103.6lbs / 47.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon       | Kind   | Speed   |
|:----------|:--------------|:-------|:--------|
| From      | [[SRD-Inkay]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Malamar.md"
flatten moves as T
where file.path = this.file.path
```
