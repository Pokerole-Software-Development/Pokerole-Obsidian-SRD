---
Ability1: Swarm
Ability2: Chlorophyll
BookSprite: SRD-sewaddle-BookSprite.png
BoxSprite: SRD-sewaddle-BoxSprite.png
DexCategory: Sewing Pokemon
DexDescription: "It is a sweet Pokemon that loves its family. It hides its head in\
  \ the leaf hood while it is sleeping. The silk they produce it\u2019s highly valued\
  \ to make expensive clothing, this makes it a popular pet for fashion designers."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Swadloon]]'
  Speed: Fast
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Overcoat
HomeSprite: SRD-sewaddle-HomeSprite.png
Image: sewaddle.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-String Shot|String Shot]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bug Bite|Bug Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[SRD-Struggle Bug|Struggle Bug]]'
- - Amateur
  - '[[SRD-Endure|Endure]]'
- - Amateur
  - '[[SRD-Sticky Web|Sticky Web]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - Ace
  - '[[SRD-Flail|Flail]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Pro
  - '[[SRD-Camouflage|Camouflage]]'
- - Pro
  - '[[SRD-Silver Wind|Silver Wind]]'
Number: 540
ShuffleToken: SRD-sewaddle-ShuffleToken.png
Type1: Bug
Type2: Grass
Weight:
  Kilograms: 2.5
  Pounds: 5.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-sewaddle-BookSprite.png|wsmall]]
> ![[SRD-sewaddle-HomeSprite.png]]
> ![[SRD-sewaddle-BoxSprite.png|htiny]]
> ![[SRD-sewaddle-ShuffleToken.png|wsmall]]


*Sewing Pokemon*
*It is a sweet Pokemon that loves its family. It hides its head in the leaf hood while it is sleeping. The silk they produce it’s highly valued to make expensive clothing, this makes it a popular pet for fashion designers.*

**DexID**:: 0540
**Name**:: Sewaddle
**Type**:: Bug / Grass
**Abilities**:: [[SRD-Swarm|Swarm]] / [[SRD-Chlorophyll|Chlorophyll]] ([[SRD-Overcoat|Overcoat]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'0" / 0.3m
**Weight**: 5.5lbs / 2.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Swadloon]] | Level  | Fast    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Sewaddle.md"
flatten moves as T
where file.path = this.file.path
```
