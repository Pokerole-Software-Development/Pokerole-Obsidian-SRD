---
Ability1: Sturdy
Ability2: Rock Head
BookSprite: SRD-bonsly-BookSprite.png
BoxSprite: SRD-bonsly-BoxSprite.png
DexCategory: Bonsai Pokemon
DexDescription: "They thrive in arid places. It looks like it\u2019s crying all the\
  \ time but it\u2019s actually adjusting the moisture of its body and releasing excess\
  \ water. Over time they become excellent at impersonating trees."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Move: Mimic
  Pokemon: '[[SRD-Sudowoodo]]'
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Rattled
HomeSprite: SRD-bonsly-HomeSprite.png
Image: bonsly.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Fake Tears|Fake Tears]]'
- - Starter
  - '[[SRD-Copycat|Copycat]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Flail|Flail]]'
- - Beginner
  - '[[SRD-Low Kick|Low Kick]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Rock Throw|Rock Throw]]'
- - Amateur
  - '[[SRD-Mimic|Mimic]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Rock Tomb|Rock Tomb]]'
- - Amateur
  - '[[SRD-Tearful Look|Tearful Look]]'
- - Amateur
  - '[[SRD-Block|Block]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Ace
  - '[[SRD-Counter|Counter]]'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Sand Tomb|Sand Tomb]]'
- - Pro
  - '[[SRD-Rest|Rest]]'
- - Pro
  - '[[SRD-Foul Play|Foul Play]]'
Number: 438
ShuffleToken: SRD-bonsly-ShuffleToken.png
Type1: Rock
Type2: ''
Weight:
  Kilograms: 15.0
  Pounds: 33.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-bonsly-BookSprite.png|wsmall]]
> ![[SRD-bonsly-HomeSprite.png]]
> ![[SRD-bonsly-BoxSprite.png|htiny]]
> ![[SRD-bonsly-ShuffleToken.png|wsmall]]


*Bonsai Pokemon*
*They thrive in arid places. It looks like it’s crying all the time but it’s actually adjusting the moisture of its body and releasing excess water. Over time they become excellent at impersonating trees.*

**DexID**:: 0438
**Name**:: Bonsly
**Type**:: Rock
**Abilities**:: [[SRD-Sturdy|Sturdy]] / [[SRD-Rock Head|Rock Head]] ([[SRD-Rattled|Rattled]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::2) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::2)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'6" / 0.5m
**Weight**: 33.1lbs / 15.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon           | Kind   | Move   |
|:----------|:------------------|:-------|:-------|
| To        | [[SRD-Sudowoodo]] | Level  | Mimic  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Bonsly.md"
flatten moves as T
where file.path = this.file.path
```
