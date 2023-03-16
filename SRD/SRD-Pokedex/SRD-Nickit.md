---
Ability1: Run Away
Ability2: Unburden
BookSprite: SRD-nickit-BookSprite.png
BoxSprite: SRD-nickit-BoxSprite.png
DexCategory: Fox Pokemon
DexDescription: "Cunning and cautious, Nickit survive by stealing food. It erases\
  \ its tracks with swipes of its tail so it\u2019s very difficult to track one. They\
  \ have thrived in the cities and come at night to steal from stores."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Thievul]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Stakeout
HomeSprite: SRD-nickit-HomeSprite.png
Image: nickit.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Beat Up|Beat Up]]'
- - Beginner
  - '[[SRD-Hone Claws|Hone Claws]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Snarl|Snarl]]'
- - Amateur
  - '[[SRD-Assurance|Assurance]]'
- - Amateur
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[SRD-Tail Slap|Tail Slap]]'
- - Ace
  - '[[SRD-Foul Play|Foul Play]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Play Rough|Play Rough]]'
- - Pro
  - '[[SRD-Knock Off|Knock Off]]'
- - Pro
  - '[[SRD-Fake Tears|Fake Tears]]'
Number: 827
ShuffleToken: SRD-nickit-ShuffleToken.png
Type1: Dark
Type2: ''
Weight:
  Kilograms: 8.9
  Pounds: 19.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-nickit-BookSprite.png|wsmall]]
> ![[SRD-nickit-HomeSprite.png]]
> ![[SRD-nickit-BoxSprite.png|htiny]]
> ![[SRD-nickit-ShuffleToken.png|wsmall]]


*Fox Pokemon*
*Cunning and cautious, Nickit survive by stealing food. It erases its tracks with swipes of its tail so it’s very difficult to track one. They have thrived in the cities and come at night to steal from stores.*

**DexID**:: 0827
**Name**:: Nickit
**Type**:: Dark
**Abilities**:: [[SRD-Run Away|Run Away]] / [[SRD-Unburden|Unburden]] ([[SRD-Stakeout|Stakeout]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 19.6lbs / 8.9kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Thievul]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Nickit.md"
flatten moves as T
where file.path = this.file.path
```
