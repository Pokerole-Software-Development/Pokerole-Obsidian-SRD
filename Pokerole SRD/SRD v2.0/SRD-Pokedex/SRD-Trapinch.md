---
Ability1: Hyper Cutter
Ability2: Arena Trap
BookSprite: SRD-trapinch-BookSprite.png
BoxSprite: SRD-trapinch-BoxSprite.png
DexCategory: Ant Pit Pokemon
DexDescription: "Their nest is like a bowl pit dug in sand. Trapinches wait for prey\
  \ to tumble down their pit, later to be crushed between this Pokemon\u2019s jaws.\
  \ Beware of them as their bite can cause serious damage."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Vibrava]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Sheer Force
HomeSprite: SRD-trapinch-HomeSprite.png
Image: trapinch.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Feint Attack|Feint Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sand Tomb|Sand Tomb]]'
- - Amateur
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Amateur
  - '[[SRD-Bide|Bide]]'
- - Amateur
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Amateur
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Amateur
  - '[[SRD-Dig|Dig]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Earth Power|Earth Power]]'
- - Amateur
  - '[[SRD-Sandstorm|Sandstorm]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Feint|Feint]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - Ace
  - '[[SRD-Fissure|Fissure]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Bug Bite|Bug Bite]]'
- - Pro
  - '[[SRD-Headbutt|Headbutt]]'
- - Pro
  - '[[SRD-Giga Drain|Giga Drain]]'
Number: 328
ShuffleToken: SRD-trapinch-ShuffleToken.png
Type1: Ground
Type2: ''
Weight:
  Kilograms: 15.0
  Pounds: 33.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-trapinch-BookSprite.png|wsmall]]
> ![[SRD-trapinch-HomeSprite.png]]
> ![[SRD-trapinch-BoxSprite.png|htiny]]
> ![[SRD-trapinch-ShuffleToken.png|wsmall]]


*Ant Pit Pokemon*
*Their nest is like a bowl pit dug in sand. Trapinches wait for prey to tumble down their pit, later to be crushed between this Pokemon’s jaws. Beware of them as their bite can cause serious damage.*

**DexID**:: 0328
**Name**:: Trapinch
**Type**:: Ground
**Abilities**:: [[SRD-Hyper Cutter|Hyper Cutter]] / [[SRD-Arena Trap|Arena Trap]] ([[SRD-Sheer Force|Sheer Force]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::2) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'3" / 0.7m
**Weight**: 33.1lbs / 15.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Vibrava]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Trapinch.md"
flatten moves as T
where file.path = this.file.path
```
