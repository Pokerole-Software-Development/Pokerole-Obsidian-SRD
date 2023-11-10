---
Ability1: Run Away
Ability2: Keen Eye
BookSprite: SRD-watchog-BookSprite.png
BoxSprite: SRD-watchog-BoxSprite.png
DexCategory: Lookout Pokemon
DexDescription: Their fur has a luminescent property. They make the patterns on their
  bodies glow in order to threaten predators. Their keen eyesight allows them to see
  in the dark. They are also good diggers.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Patrat]]'
  Speed: Fast
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Analytic
HomeSprite: SRD-watchog-HomeSprite.png
Image: watchog.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Low Kick|Low Kick]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Detect|Detect]]'
- - Beginner
  - '[[SRD-Bide|Bide]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Rototiller|Rototiller]]'
- - Amateur
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Super Fang|Super Fang]]'
- - Amateur
  - '[[SRD-After You|After You]]'
- - Amateur
  - '[[SRD-Psych Up|Psych Up]]'
- - Amateur
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Amateur
  - '[[SRD-Mean Look|Mean Look]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hyper Fang|Hyper Fang]]'
- - Ace
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Ace
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Ace
  - '[[SRD-Slam|Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fire Punch|Fire Punch]]'
- - Pro
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Pro
  - '[[SRD-Revenge|Revenge]]'
Number: 505
ShuffleToken: SRD-watchog-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 27.0
  Pounds: 59.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-watchog-BookSprite.png|wsmall]]
> ![[SRD-watchog-HomeSprite.png]]
> ![[SRD-watchog-BoxSprite.png|htiny]]
> ![[SRD-watchog-ShuffleToken.png|wsmall]]


*Lookout Pokemon*
*Their fur has a luminescent property. They make the patterns on their bodies glow in order to threaten predators. Their keen eyesight allows them to see in the dark. They are also good diggers.*

**DexID**:: 0505
**Name**:: Watchog
**Type**:: Normal
**Abilities**:: [[SRD-Run Away|Run Away]] / [[SRD-Keen Eye|Keen Eye]] ([[SRD-Analytic|Analytic]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'6" / 1.1m
**Weight**: 59.5lbs / 27.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Patrat]] | Level  | Fast    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Watchog.md"
flatten moves as T
where file.path = this.file.path
```
