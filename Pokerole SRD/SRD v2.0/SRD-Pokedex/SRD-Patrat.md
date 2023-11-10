---
Ability1: Run Away
Ability2: Keen Eye
BookSprite: SRD-patrat-BookSprite.png
BoxSprite: SRD-patrat-BoxSprite.png
DexCategory: Scout Pokemon
DexDescription: They live in grass fields in big groups. One of them is always looking
  out for predators. The group gathers food they store on their cheeks to bring it
  back home. They are wary and alert all the time.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Watchog]]'
  Speed: Fast
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Analytic
HomeSprite: SRD-patrat-HomeSprite.png
Image: patrat.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Bide|Bide]]'
- - Beginner
  - '[[SRD-Detect|Detect]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Amateur
  - '[[SRD-Super Fang|Super Fang]]'
- - Amateur
  - '[[SRD-After You|After You]]'
- - Amateur
  - '[[SRD-Work Up|Work Up]]'
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
  - '[[SRD-Screech|Screech]]'
- - Pro
  - '[[SRD-Seed Bomb|Seed Bomb]]'
- - Pro
  - '[[SRD-Aqua Tail|Aqua Tail]]'
Number: 504
ShuffleToken: SRD-patrat-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 11.6
  Pounds: 25.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-patrat-BookSprite.png|wsmall]]
> ![[SRD-patrat-HomeSprite.png]]
> ![[SRD-patrat-BoxSprite.png|htiny]]
> ![[SRD-patrat-ShuffleToken.png|wsmall]]


*Scout Pokemon*
*They live in grass fields in big groups. One of them is always looking out for predators. The group gathers food they store on their cheeks to bring it back home. They are wary and alert all the time.*

**DexID**:: 0504
**Name**:: Patrat
**Type**:: Normal
**Abilities**:: [[SRD-Run Away|Run Away]] / [[SRD-Keen Eye|Keen Eye]] ([[SRD-Analytic|Analytic]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'6" / 0.5m
**Weight**: 25.6lbs / 11.6kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Watchog]] | Level  | Fast    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Patrat.md"
flatten moves as T
where file.path = this.file.path
```
