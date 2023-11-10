---
Ability1: Keen Eye
Ability2: Skill Link
BookSprite: SRD-toucannon-BookSprite.png
BoxSprite: SRD-toucannon-BoxSprite.png
DexCategory: Blade Quill Pokemon
DexDescription: It can store and expel an extremely hot gas through its beak that
  ignites easily. The berry seeds it shoots can pierce boulders, leaving perfectly
  round holes on them. Fortunately, they nest deep in the jungle.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Trumbeak]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Sheer Force
HomeSprite: SRD-toucannon-HomeSprite.png
Image: toucannon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Peck|Peck]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Echoed Voice|Echoed Voice]]'
- - Beginner
  - '[[SRD-Rock Smash|Rock Smash]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Amateur
  - '[[SRD-Supersonic|Supersonic]]'
- - Amateur
  - '[[SRD-Pluck|Pluck]]'
- - Amateur
  - '[[SRD-Roost|Roost]]'
- - Amateur
  - '[[SRD-Fury Attack|Fury Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Beak Blast|Beak Blast]]'
- - Ace
  - '[[SRD-Drill Peck|Drill Peck]]'
- - Ace
  - '[[SRD-Bullet Seed|Bullet Seed]]'
- - Ace
  - '[[SRD-Feather Dance|Feather Dance]]'
- - Ace
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Boomburst|Boomburst]]'
- - Pro
  - '[[SRD-Tailwind|Tailwind]]'
- - Pro
  - '[[SRD-Brave Bird|Brave Bird]]'
Number: 733
ShuffleToken: SRD-toucannon-ShuffleToken.png
Type1: Normal
Type2: Flying
Weight:
  Kilograms: 26.0
  Pounds: 57.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-toucannon-BookSprite.png|wsmall]]
> ![[SRD-toucannon-HomeSprite.png]]
> ![[SRD-toucannon-BoxSprite.png|htiny]]
> ![[SRD-toucannon-ShuffleToken.png|wsmall]]


*Blade Quill Pokemon*
*It can store and expel an extremely hot gas through its beak that ignites easily. The berry seeds it shoots can pierce boulders, leaving perfectly round holes on them. Fortunately, they nest deep in the jungle.*

**DexID**:: 0733
**Name**:: Toucannon
**Type**:: Normal / Flying
**Abilities**:: [[SRD-Keen Eye|Keen Eye]] / [[SRD-Skill Link|Skill Link]] ([[SRD-Sheer Force|Sheer Force]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'6" / 1.1m
**Weight**: 57.3lbs / 26.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Trumbeak]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Toucannon.md"
flatten moves as T
where file.path = this.file.path
```
