---
Ability1: Natural Cure
Ability2: Serene Grace
BookSprite: SRD-happiny-BookSprite.png
BoxSprite: SRD-happiny-BoxSprite.png
DexCategory: Playhouse Pokemon
DexDescription: It is not common to see Happinies. This baby Pokemon cannot produce
  eggs yet, so she searches for white stones and carries them on its pouch. It likes
  to look pretty and tries to always be adorable.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Oval Stone
  Kind: Level
  Pokemon: '[[SRD-Chansey]]'
GenderType: F
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Friend Guard
HomeSprite: SRD-happiny-HomeSprite.png
Image: happiny.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Charm|Charm]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Copycat|Copycat]]'
- - Beginner
  - '[[SRD-Refresh|Refresh]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sweet Kiss|Sweet Kiss]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Pro
  - '[[SRD-Present|Present]]'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
Number: 440
ShuffleToken: SRD-happiny-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 24.4
  Pounds: 53.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-happiny-BookSprite.png|wsmall]]
> ![[SRD-happiny-HomeSprite.png]]
> ![[SRD-happiny-BoxSprite.png|htiny]]
> ![[SRD-happiny-ShuffleToken.png|wsmall]]


*Playhouse Pokemon*
*It is not common to see Happinies. This baby Pokemon cannot produce eggs yet, so she searches for white stones and carries them on its pouch. It likes to look pretty and tries to always be adorable.*

**DexID**:: 0440
**Name**:: Happiny
**Type**:: Normal
**Abilities**:: [[SRD-Natural Cure|Natural Cure]] / [[SRD-Serene Grace|Serene Grace]] ([[SRD-Friend Guard|Friend Guard]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::2)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::2)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::2)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'0" / 0.6m
**Weight**: 53.8lbs / 24.4kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon         | Kind   | Item       |
|:----------|:----------------|:-------|:-----------|
| To        | [[SRD-Chansey]] | Level  | Oval Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Happiny.md"
flatten moves as T
where file.path = this.file.path
```
