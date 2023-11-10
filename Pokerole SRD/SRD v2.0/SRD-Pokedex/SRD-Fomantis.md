---
Ability1: Leaf Guard
Ability2: ''
BookSprite: SRD-fomantis-BookSprite.png
BoxSprite: SRD-fomantis-BoxSprite.png
DexCategory: Sickle Grass Pokemon
DexDescription: They sleep during the day, absorbing sunlight in a flower meadow;
  by night they become active and search for another spot to sleep. Their arms are
  made or sharp grass leaves to defend themselves.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Lurantis]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Contrary
HomeSprite: SRD-fomantis-HomeSprite.png
Image: fomantis.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - Starter
  - '[[SRD-Leafage|Leafage]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Beginner
  - '[[SRD-Growth|Growth]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ingrain|Ingrain]]'
- - Amateur
  - '[[SRD-Leaf Blade|Leaf Blade]]'
- - Amateur
  - '[[SRD-Synthesis|Synthesis]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Solar Beam|Solar Beam]]'
- - Ace
  - '[[SRD-Sunny Day|Sunny Day]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Weather Ball|Weather Ball]]'
- - Pro
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Pro
  - '[[SRD-Aromatherapy|Aromatherapy]]'
Number: 753
ShuffleToken: SRD-fomantis-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 1.5
  Pounds: 3.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-fomantis-BookSprite.png|wsmall]]
> ![[SRD-fomantis-HomeSprite.png]]
> ![[SRD-fomantis-BoxSprite.png|htiny]]
> ![[SRD-fomantis-ShuffleToken.png|wsmall]]


*Sickle Grass Pokemon*
*They sleep during the day, absorbing sunlight in a flower meadow; by night they become active and search for another spot to sleep. Their arms are made or sharp grass leaves to defend themselves.*

**DexID**:: 0753
**Name**:: Fomantis
**Type**:: Grass
**Abilities**:: [[SRD-Leaf Guard|Leaf Guard]] ([[SRD-Contrary|Contrary]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 3.3lbs / 1.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Lurantis]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Fomantis.md"
flatten moves as T
where file.path = this.file.path
```
