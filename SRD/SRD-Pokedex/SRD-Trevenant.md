---
Ability1: Natural Cure
Ability2: Frisk
BookSprite: SRD-trevenant-BookSprite.png
BoxSprite: SRD-trevenant-BoxSprite.png
DexCategory: Elder Tree Pokemon
DexDescription: "Using its roots as a nervous system it controls the trees in the\
  \ forest. It\u2019s kind to the Pokemon that reside inside its body but it is ruthless\
  \ to anyone that harms its forest, turning them into haunted trees forever."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Trade
  Pokemon: '[[SRD-Phantump]]'
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Harvest
HomeSprite: SRD-trevenant-HomeSprite.png
Image: trevenant.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Growth|Growth]]'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Horn Leech|Horn Leech]]'
- - Amateur
  - '[[SRD-Ingrain|Ingrain]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Will-O-Wisp|Will-O-Wisp]]'
- - Amateur
  - '[[SRD-Forest''s Curse|Forest''s Curse]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Destiny Bond|Destiny Bond]]'
- - Ace
  - '[[SRD-Phantom Force|Phantom Force]]'
- - Ace
  - '[[SRD-Wood Hammer|Wood Hammer]]'
- - Ace
  - '[[SRD-Shadow Claw|Shadow Claw]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Grudge|Grudge]]'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
- - Pro
  - '[[SRD-Imprison|Imprison]]'
Number: 709
ShuffleToken: SRD-trevenant-ShuffleToken.png
Type1: Ghost
Type2: Grass
Weight:
  Kilograms: 71.0
  Pounds: 156.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-trevenant-BookSprite.png|wsmall]]
> ![[SRD-trevenant-HomeSprite.png]]
> ![[SRD-trevenant-BoxSprite.png|htiny]]
> ![[SRD-trevenant-ShuffleToken.png|wsmall]]


*Elder Tree Pokemon*
*Using its roots as a nervous system it controls the trees in the forest. It’s kind to the Pokemon that reside inside its body but it is ruthless to anyone that harms its forest, turning them into haunted trees forever.*

**DexID**:: 0709
**Name**:: Trevenant
**Type**:: Ghost / Grass
**Abilities**:: [[SRD-Natural Cure|Natural Cure]] / [[SRD-Frisk|Frisk]] ([[SRD-Harvest|Harvest]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'9" / 1.5m
**Weight**: 156.5lbs / 71.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon          | Kind   |
|:----------|:-----------------|:-------|
| From      | [[SRD-Phantump]] | Trade  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Trevenant.md"
flatten moves as T
where file.path = this.file.path
```
