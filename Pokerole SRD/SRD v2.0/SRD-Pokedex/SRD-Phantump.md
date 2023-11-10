---
Ability1: Natural Cure
Ability2: Frisk
BookSprite: SRD-phantump-BookSprite.png
BoxSprite: SRD-phantump-BoxSprite.png
DexCategory: Stump Pokemon
DexDescription: According to the old tales, these Pokemon are stumps possessed by
  the spirits of children who were lost in the forest. They prefer to live in abandoned
  woods and lure people to the darkness to play with them.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Trade
  Pokemon: '[[SRD-Trevenant]]'
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Harvest
HomeSprite: SRD-phantump-HomeSprite.png
Image: phantump.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - Beginner
  - '[[SRD-Growth|Growth]]'
- - '---------------------------'
  - '---------------------------'
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
  - '[[SRD-Horn Leech|Horn Leech]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Seed Bomb|Seed Bomb]]'
- - Pro
  - '[[SRD-Venom Drench|Venom Drench]]'
- - Pro
  - '[[SRD-Worry Seed|Worry Seed]]'
Number: 708
ShuffleToken: SRD-phantump-ShuffleToken.png
Type1: Ghost
Type2: Grass
Weight:
  Kilograms: 7.0
  Pounds: 15.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-phantump-BookSprite.png|wsmall]]
> ![[SRD-phantump-HomeSprite.png]]
> ![[SRD-phantump-BoxSprite.png|htiny]]
> ![[SRD-phantump-ShuffleToken.png|wsmall]]


*Stump Pokemon*
*According to the old tales, these Pokemon are stumps possessed by the spirits of children who were lost in the forest. They prefer to live in abandoned woods and lure people to the darkness to play with them.*

**DexID**:: 0708
**Name**:: Phantump
**Type**:: Ghost / Grass
**Abilities**:: [[SRD-Natural Cure|Natural Cure]] / [[SRD-Frisk|Frisk]] ([[SRD-Harvest|Harvest]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 15.4lbs / 7.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon           | Kind   |
|:----------|:------------------|:-------|
| To        | [[SRD-Trevenant]] | Trade  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Phantump.md"
flatten moves as T
where file.path = this.file.path
```
