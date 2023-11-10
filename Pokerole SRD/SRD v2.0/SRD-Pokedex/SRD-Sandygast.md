---
Ability1: Water Compaction
Ability2: ''
BookSprite: SRD-sandygast-BookSprite.png
BoxSprite: SRD-sandygast-BoxSprite.png
DexCategory: Sand Heap Pokemon
DexDescription: "Some departed soul made a child\u2019s sand mound its vessel. Anyone\
  \ who puts their hand inside its mouth will have its vital energy absorbed and its\
  \ mind possessed to add more sand until they collapse."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Palossand]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Sand Veil
HomeSprite: SRD-sandygast-HomeSprite.png
Image: sandygast.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Harden|Harden]]'
- - Starter
  - '[[SRD-Absorb|Absorb]]'
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - Starter
  - '[[SRD-Sand Attack|Sand Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sand Tomb|Sand Tomb]]'
- - Beginner
  - '[[SRD-Mega Drain|Mega Drain]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Amateur
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Amateur
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Earth Power|Earth Power]]'
- - Ace
  - '[[SRD-Shore Up|Shore Up]]'
- - Ace
  - '[[SRD-Sandstorm|Sandstorm]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Stockpile|Stockpile]]'
- - Pro
  - '[[SRD-Spit Up|Spit Up]]'
- - Pro
  - '[[SRD-Swallow|Swallow]]'
Number: 769
ShuffleToken: SRD-sandygast-ShuffleToken.png
Type1: Ghost
Type2: Ground
Weight:
  Kilograms: 70.0
  Pounds: 154.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-sandygast-BookSprite.png|wsmall]]
> ![[SRD-sandygast-HomeSprite.png]]
> ![[SRD-sandygast-BoxSprite.png|htiny]]
> ![[SRD-sandygast-ShuffleToken.png|wsmall]]


*Sand Heap Pokemon*
*Some departed soul made a child’s sand mound its vessel. Anyone who puts their hand inside its mouth will have its vital energy absorbed and its mind possessed to add more sand until they collapse.*

**DexID**:: 0769
**Name**:: Sandygast
**Type**:: Ghost / Ground
**Abilities**:: [[SRD-Water Compaction|Water Compaction]] ([[SRD-Sand Veil|Sand Veil]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::2) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'6" / 0.5m
**Weight**: 154.3lbs / 70.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Palossand]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Sandygast.md"
flatten moves as T
where file.path = this.file.path
```
