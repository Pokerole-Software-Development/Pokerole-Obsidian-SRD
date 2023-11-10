---
Ability1: Overgrow
Ability2: ''
BookSprite: SRD-treecko-BookSprite.png
BoxSprite: SRD-treecko-BoxSprite.png
DexCategory: Wood Gecko Pokemon
DexDescription: They climb trees with their spiked feet. They remain cool under stress,
  calmed under pressure and collected when endangered. They are found protecting the
  trees ferociously.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Grovyle]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Unburden
HomeSprite: SRD-treecko-HomeSprite.png
Image: treecko.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Pound|Pound]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Absorb|Absorb]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Pursuit|Pursuit]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Detect|Detect]]'
- - Ace
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Ace
  - '[[SRD-Endeavor|Endeavor]]'
- - Ace
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Ace
  - '[[SRD-Energy Ball|Energy Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Iron Tail|Iron Tail]]'
- - Pro
  - '[[SRD-Bullet Seed|Bullet Seed]]'
- - Pro
  - '[[SRD-Grass Pledge|Grass Pledge]]'
Number: 252
ShuffleToken: SRD-treecko-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 5.0
  Pounds: 11.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-treecko-BookSprite.png|wsmall]]
> ![[SRD-treecko-HomeSprite.png]]
> ![[SRD-treecko-BoxSprite.png|htiny]]
> ![[SRD-treecko-ShuffleToken.png|wsmall]]


*Wood Gecko Pokemon*
*They climb trees with their spiked feet. They remain cool under stress, calmed under pressure and collected when endangered. They are found protecting the trees ferociously.*

**DexID**:: 0252
**Name**:: Treecko
**Type**:: Grass
**Abilities**:: [[SRD-Overgrow|Overgrow]] ([[SRD-Unburden|Unburden]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'6" / 0.5m
**Weight**: 11.0lbs / 5.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Grovyle]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Treecko.md"
flatten moves as T
where file.path = this.file.path
```
