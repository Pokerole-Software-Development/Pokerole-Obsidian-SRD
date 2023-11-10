---
Ability1: Chlorophyll
Ability2: ''
BookSprite: SRD-oddish-BookSprite.png
BoxSprite: SRD-oddish-BoxSprite.png
DexCategory: Weed Pokemon
DexDescription: This Pokemon grows by absorbing moonlight. During daytime, it buries
  itself in the ground, leaving only its leaves exposed to avoid detection by its
  predators. You can locate it by the smell its leaves release.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Gloom]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Run Away
HomeSprite: SRD-oddish-HomeSprite.png
Image: oddish.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growth|Growth]]'
- - Starter
  - '[[SRD-Absorb|Absorb]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Beginner
  - '[[SRD-Acid|Acid]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Poison Powder|Poison Powder]]'
- - Amateur
  - '[[SRD-Stun Spore|Stun Spore]]'
- - Amateur
  - '[[SRD-Sleep Powder|Sleep Powder]]'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Amateur
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Amateur
  - '[[SRD-Moonlight|Moonlight]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Ace
  - '[[SRD-Petal Dance|Petal Dance]]'
- - Ace
  - '[[SRD-Moonblast|Moonblast]]'
- - Ace
  - '[[SRD-Grassy Terrain|Grassy Terrain]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Charm|Charm]]'
- - Pro
  - '[[SRD-Gastro Acid|Gastro Acid]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
Number: 43
ShuffleToken: SRD-oddish-ShuffleToken.png
Type1: Grass
Type2: Poison
Weight:
  Kilograms: 5.4
  Pounds: 11.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-oddish-BookSprite.png|wsmall]]
> ![[SRD-oddish-HomeSprite.png]]
> ![[SRD-oddish-BoxSprite.png|htiny]]
> ![[SRD-oddish-ShuffleToken.png|wsmall]]


*Weed Pokemon*
*This Pokemon grows by absorbing moonlight. During daytime, it buries itself in the ground, leaving only its leaves exposed to avoid detection by its predators. You can locate it by the smell its leaves release.*

**DexID**:: 0043
**Name**:: Oddish
**Type**:: Grass / Poison
**Abilities**:: [[SRD-Chlorophyll|Chlorophyll]] ([[SRD-Run Away|Run Away]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'6" / 0.5m
**Weight**: 11.9lbs / 5.4kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon       | Kind   | Speed   |
|:----------|:--------------|:-------|:--------|
| To        | [[SRD-Gloom]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Oddish.md"
flatten moves as T
where file.path = this.file.path
```
