---
Ability1: Contrary
Ability2: Suction Cups
BookSprite: SRD-inkay-BookSprite.png
BoxSprite: SRD-inkay-BoxSprite.png
DexCategory: Revolving Pokemon
DexDescription: "It lives at the darkest parts of the sea. The spots on its body flash\
  \ to confuse predators and give it the opportunity to scuttle away. From time to\
  \ time it likes to float upside down, it means it\u2019s close to evolving."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Malamar]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Infiltrator
HomeSprite: SRD-inkay-HomeSprite.png
Image: inkay.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Peck|Peck]]'
- - Starter
  - '[[SRD-Constrict|Constrict]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Reflect|Reflect]]'
- - Beginner
  - '[[SRD-Foul Play|Foul Play]]'
- - '---------------------------'
  - '---------------------------'
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
Number: 686
ShuffleToken: SRD-inkay-ShuffleToken.png
Type1: Dark
Type2: Psychic
Weight:
  Kilograms: 3.5
  Pounds: 7.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-inkay-BookSprite.png|wsmall]]
> ![[SRD-inkay-HomeSprite.png]]
> ![[SRD-inkay-BoxSprite.png|htiny]]
> ![[SRD-inkay-ShuffleToken.png|wsmall]]


*Revolving Pokemon*
*It lives at the darkest parts of the sea. The spots on its body flash to confuse predators and give it the opportunity to scuttle away. From time to time it likes to float upside down, it means it’s close to evolving.*

**DexID**:: 0686
**Name**:: Inkay
**Type**:: Dark / Psychic
**Abilities**:: [[SRD-Contrary|Contrary]] / [[SRD-Suction Cups|Suction Cups]] ([[SRD-Infiltrator|Infiltrator]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 7.7lbs / 3.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Malamar]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Inkay.md"
flatten moves as T
where file.path = this.file.path
```
