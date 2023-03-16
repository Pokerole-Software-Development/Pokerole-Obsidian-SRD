---
Ability1: Overgrow
Ability2: ''
BookSprite: SRD-servine-BookSprite.png
BoxSprite: SRD-servine-BoxSprite.png
DexCategory: Grass Snake Pokemon
DexDescription: It moves along the ground by sliding. Its swift movements befuddle
  its foes, then attacks with a vine whip. It always keeps itself clean and it demands
  care from its trainer, otherwise it will misbehave.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Snivy]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Serperior]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Contrary
HomeSprite: SRD-servine-HomeSprite.png
Image: servine.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Vine Whip|Vine Whip]]'
- - Beginner
  - '[[SRD-Wrap|Wrap]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Growth|Growth]]'
- - Amateur
  - '[[SRD-Leaf Tornado|Leaf Tornado]]'
- - Amateur
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - Amateur
  - '[[SRD-Leaf Blade|Leaf Blade]]'
- - Amateur
  - '[[SRD-Coil|Coil]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Ace
  - '[[SRD-Wring Out|Wring Out]]'
- - Ace
  - '[[SRD-Gastro Acid|Gastro Acid]]'
- - Ace
  - '[[SRD-Leaf Storm|Leaf Storm]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Grass Pledge|Grass Pledge]]'
- - Pro
  - '[[SRD-Synthesis|Synthesis]]'
- - Pro
  - '[[SRD-Twister|Twister]]'
Number: 496
ShuffleToken: SRD-servine-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 16.0
  Pounds: 35.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-servine-BookSprite.png|wsmall]]
> ![[SRD-servine-HomeSprite.png]]
> ![[SRD-servine-BoxSprite.png|htiny]]
> ![[SRD-servine-ShuffleToken.png|wsmall]]


*Grass Snake Pokemon*
*It moves along the ground by sliding. Its swift movements befuddle its foes, then attacks with a vine whip. It always keeps itself clean and it demands care from its trainer, otherwise it will misbehave.*

**DexID**:: 0496
**Name**:: Servine
**Type**:: Grass
**Abilities**:: [[SRD-Overgrow|Overgrow]] ([[SRD-Contrary|Contrary]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'6" / 0.8m
**Weight**: 35.3lbs / 16.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Snivy]]     | Level  | Medium  |
| To        | [[SRD-Serperior]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Servine.md"
flatten moves as T
where file.path = this.file.path
```
