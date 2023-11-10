---
Ability1: Insomnia
Ability2: Super Luck
BookSprite: SRD-murkrow-BookSprite.png
BoxSprite: SRD-murkrow-BoxSprite.png
DexCategory: Darkness Pokemon
DexDescription: Murkrows are feared and loathed as the alleged bearers of ill fortune.
  This Pokemon will steal anything that sparkles. They are infamous for luring people
  and get them lost in the mountains.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Dusk Stone
  Kind: Stone
  Pokemon: '[[SRD-Honchkrow]]'
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Prankster
HomeSprite: SRD-murkrow-HomeSprite.png
Image: murkrow.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Peck|Peck]]'
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Pursuit|Pursuit]]'
- - Beginner
  - '[[SRD-Haze|Haze]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Wing Attack|Wing Attack]]'
- - Amateur
  - '[[SRD-Night Shade|Night Shade]]'
- - Amateur
  - '[[SRD-Assurance|Assurance]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Mean Look|Mean Look]]'
- - Amateur
  - '[[SRD-Foul Play|Foul Play]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Tailwind|Tailwind]]'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Ace
  - '[[SRD-Torment|Torment]]'
- - Ace
  - '[[SRD-Quash|Quash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Drill Peck|Drill Peck]]'
- - Pro
  - '[[SRD-Roost|Roost]]'
- - Pro
  - '[[SRD-Perish Song|Perish Song]]'
Number: 198
ShuffleToken: SRD-murkrow-ShuffleToken.png
Type1: Dark
Type2: Flying
Weight:
  Kilograms: 2.1
  Pounds: 4.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-murkrow-BookSprite.png|wsmall]]
> ![[SRD-murkrow-HomeSprite.png]]
> ![[SRD-murkrow-BoxSprite.png|htiny]]
> ![[SRD-murkrow-ShuffleToken.png|wsmall]]


*Darkness Pokemon*
*Murkrows are feared and loathed as the alleged bearers of ill fortune. This Pokemon will steal anything that sparkles. They are infamous for luring people and get them lost in the mountains.*

**DexID**:: 0198
**Name**:: Murkrow
**Type**:: Dark / Flying
**Abilities**:: [[SRD-Insomnia|Insomnia]] / [[SRD-Super Luck|Super Luck]] ([[SRD-Prankster|Prankster]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'6" / 0.5m
**Weight**: 4.6lbs / 2.1kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon           | Kind   | Item       |
|:----------|:------------------|:-------|:-----------|
| To        | [[SRD-Honchkrow]] | Stone  | Dusk Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Murkrow.md"
flatten moves as T
where file.path = this.file.path
```
