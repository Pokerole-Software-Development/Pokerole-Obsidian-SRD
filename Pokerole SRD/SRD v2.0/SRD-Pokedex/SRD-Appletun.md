---
Ability1: Ripen
Ability2: Gluttony
BookSprite: SRD-appletun-BookSprite.png
BoxSprite: SRD-appletun-BoxSprite.png
DexCategory: Apple Nectar Pokemon
DexDescription: Eating a sweet apple caused its evolution. A nectarous scent wafts
  from its body, luring in the bug Pokemon it preys on, but it also attracts other
  Pokemon who eat the skins atop of its back.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Tart Apple
  Kind: Item
  Pokemon: '[[SRD-Applin]]'
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Thick Fat
HomeSprite: SRD-appletun-HomeSprite.png
Image: appletun.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Withdraw|Withdraw]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - Beginner
  - '[[SRD-Headbutt|Headbutt]]'
- - Beginner
  - '[[SRD-Recycle|Recycle]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Growth|Growth]]'
- - Amateur
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Stomp|Stomp]]'
- - Amateur
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Bullet Seed|Bullet Seed]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Recover|Recover]]'
- - Ace
  - '[[SRD-Apple Acid|Apple Acid]]'
- - Ace
  - '[[SRD-Body Slam|Body Slam]]'
- - Ace
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Ace
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Ace
  - '[[SRD-Energy Ball|Energy Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Pro
  - '[[SRD-Solar Beam|Solar Beam]]'
- - Pro
  - '[[SRD-Draco Meteor|Draco Meteor]]'
Number: 842
ShuffleToken: SRD-appletun-ShuffleToken.png
Type1: Grass
Type2: Dragon
Weight:
  Kilograms: 13.0
  Pounds: 28.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-appletun-BookSprite.png|wsmall]]
> ![[SRD-appletun-HomeSprite.png]]
> ![[SRD-appletun-BoxSprite.png|htiny]]
> ![[SRD-appletun-ShuffleToken.png|wsmall]]


*Apple Nectar Pokemon*
*Eating a sweet apple caused its evolution. A nectarous scent wafts from its body, luring in the bug Pokemon it preys on, but it also attracts other Pokemon who eat the skins atop of its back.*

**DexID**:: 0842
**Name**:: Appletun
**Type**:: Grass / Dragon
**Abilities**:: [[SRD-Ripen|Ripen]] / [[SRD-Gluttony|Gluttony]] ([[SRD-Thick Fat|Thick Fat]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 1'3" / 0.4m
**Weight**: 28.7lbs / 13.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon        | Kind   | Item       |
|:----------|:---------------|:-------|:-----------|
| From      | [[SRD-Applin]] | Item   | Tart Apple |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Appletun.md"
flatten moves as T
where file.path = this.file.path
```
