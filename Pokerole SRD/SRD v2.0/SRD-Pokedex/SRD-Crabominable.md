---
Ability1: Hyper Cutter
Ability2: Iron Fist
BookSprite: SRD-crabominable-BookSprite.png
BoxSprite: SRD-crabominable-BoxSprite.png
DexCategory: Woolly Crab Pokemon
DexDescription: Crawbrawlers who get lost in the snowy mountains of Alola are forced
  to evolve into a more suited form. Crabominables are not very smart and throw punches
  to friends and foes alike when they panic.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Crabrawler]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: Anger Point
HomeSprite: SRD-crabominable-HomeSprite.png
Image: crabominable.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Bubble|Bubble]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Rock Smash|Rock Smash]]'
- - Beginner
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Beginner
  - '[[SRD-Pursuit|Pursuit]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Amateur
  - '[[SRD-Power-Up Punch|Power-Up Punch]]'
- - Amateur
  - '[[SRD-Dizzy Punch|Dizzy Punch]]'
- - Amateur
  - '[[SRD-Avalanche|Avalanche]]'
- - Amateur
  - '[[SRD-Reversal|Reversal]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Ice Hammer|Ice Hammer]]'
- - Ace
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Ace
  - '[[SRD-Dynamic Punch|Dynamic Punch]]'
- - Ace
  - '[[SRD-Close Combat|Close Combat]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Endeavor|Endeavor]]'
- - Pro
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Pro
  - '[[SRD-Superpower|Superpower]]'
Number: 740
ShuffleToken: SRD-crabominable-ShuffleToken.png
Type1: Fighting
Type2: Ice
Weight:
  Kilograms: 180.0
  Pounds: 396.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-crabominable-BookSprite.png|wsmall]]
> ![[SRD-crabominable-HomeSprite.png]]
> ![[SRD-crabominable-BoxSprite.png|htiny]]
> ![[SRD-crabominable-ShuffleToken.png|wsmall]]


*Woolly Crab Pokemon*
*Crawbrawlers who get lost in the snowy mountains of Alola are forced to evolve into a more suited form. Crabominables are not very smart and throw punches to friends and foes alike when they panic.*

**DexID**:: 0740
**Name**:: Crabominable
**Type**:: Fighting / Ice
**Abilities**:: [[SRD-Hyper Cutter|Hyper Cutter]] / [[SRD-Iron Fist|Iron Fist]] ([[SRD-Anger Point|Anger Point]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 5'6" / 1.7m
**Weight**: 396.8lbs / 180.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| From      | [[SRD-Crabrawler]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Crabominable.md"
flatten moves as T
where file.path = this.file.path
```
