---
Ability1: Swarm
Ability2: Shed Skin
BookSprite: SRD-karrablast-BookSprite.png
BoxSprite: SRD-karrablast-BoxSprite.png
DexCategory: Clamping Pokemon
DexDescription: When they feel threatened, they spit an acidic liquid to drive attackers
  away. This Pokemon targets Shelmet as they compete for food. It only evolves when
  it has a Shelmet's shell as its new home.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Escavalier]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: No Guard
HomeSprite: SRD-karrablast-HomeSprite.png
Image: karrablast.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Peck|Peck]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Endure|Endure]]'
- - Beginner
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-False Swipe|False Swipe]]'
- - Amateur
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-X-Scissor|X-Scissor]]'
- - Ace
  - '[[SRD-Flail|Flail]]'
- - Ace
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Pro
  - '[[SRD-Horn Attack|Horn Attack]]'
- - Pro
  - '[[SRD-Pursuit|Pursuit]]'
Number: 588
ShuffleToken: SRD-karrablast-ShuffleToken.png
Type1: Bug
Type2: ''
Weight:
  Kilograms: 5.9
  Pounds: 13.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-karrablast-BookSprite.png|wsmall]]
> ![[SRD-karrablast-HomeSprite.png]]
> ![[SRD-karrablast-BoxSprite.png|htiny]]
> ![[SRD-karrablast-ShuffleToken.png|wsmall]]


*Clamping Pokemon*
*When they feel threatened, they spit an acidic liquid to drive attackers away. This Pokemon targets Shelmet as they compete for food. It only evolves when it has a Shelmet's shell as its new home.*

**DexID**:: 0588
**Name**:: Karrablast
**Type**:: Bug
**Abilities**:: [[SRD-Swarm|Swarm]] / [[SRD-Shed Skin|Shed Skin]] ([[SRD-No Guard|No Guard]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'6" / 0.5m
**Weight**: 13.0lbs / 5.9kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| To        | [[SRD-Escavalier]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Karrablast.md"
flatten moves as T
where file.path = this.file.path
```
