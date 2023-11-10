---
Ability1: Run Away
Ability2: Pickup
BookSprite: SRD-aipom-BookSprite.png
BoxSprite: SRD-aipom-BoxSprite.png
DexCategory: Long Tail Pokemon
DexDescription: It lives at the top of tall trees in forests and jungles. It uses
  its tail tip as a third hand. However, because the Pokemon uses its tail so much,
  its real hands become rather clumsy. It is very playful.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Ambipom]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Skill Link
HomeSprite: SRD-aipom-HomeSprite.png
Image: aipom.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Amateur
  - '[[SRD-Tickle|Tickle]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Fling|Fling]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Double Hit|Double Hit]]'
- - Ace
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Ace
  - '[[SRD-Last Resort|Last Resort]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fake Out|Fake Out]]'
- - Pro
  - '[[SRD-Beat Up|Beat Up]]'
- - Pro
  - '[[SRD-Quick Guard|Quick Guard]]'
Number: 190
ShuffleToken: SRD-aipom-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 11.5
  Pounds: 25.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-aipom-BookSprite.png|wsmall]]
> ![[SRD-aipom-HomeSprite.png]]
> ![[SRD-aipom-BoxSprite.png|htiny]]
> ![[SRD-aipom-ShuffleToken.png|wsmall]]


*Long Tail Pokemon*
*It lives at the top of tall trees in forests and jungles. It uses its tail tip as a third hand. However, because the Pokemon uses its tail so much, its real hands become rather clumsy. It is very playful.*

**DexID**:: 0190
**Name**:: Aipom
**Type**:: Normal
**Abilities**:: [[SRD-Run Away|Run Away]] / [[SRD-Pickup|Pickup]] ([[SRD-Skill Link|Skill Link]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'6" / 0.8m
**Weight**: 25.4lbs / 11.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Ambipom]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Aipom.md"
flatten moves as T
where file.path = this.file.path
```
