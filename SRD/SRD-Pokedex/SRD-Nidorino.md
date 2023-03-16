---
Ability1: Poison Point
Ability2: Rivalry
BookSprite: SRD-nidorino-BookSprite.png
BoxSprite: SRD-nidorino-BoxSprite.png
DexCategory: Poison Pin Pokemon
DexDescription: An independent and fierce creature. It roams alone in search for a
  mate and will compete with other males around. It will violently charge with a venom
  drenched horn against intruders.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Nidoran M]]'
  Speed: Medium
- Evolves: To
  Item: Moon Stone
  Kind: Stone
  Pokemon: '[[SRD-Nidoking]]'
GenderType: M
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Hustle
HomeSprite: SRD-nidorino-HomeSprite.png
Image: nidorino.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Peck|Peck]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[SRD-Double Kick|Double Kick]]'
- - Beginner
  - '[[SRD-Poison Sting|Poison Sting]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[SRD-Horn Attack|Horn Attack]]'
- - Amateur
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Amateur
  - '[[SRD-Toxic Spikes|Toxic Spikes]]'
- - Amateur
  - '[[SRD-Poison Jab|Poison Jab]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Flatter|Flatter]]'
- - Ace
  - '[[SRD-Captivate|Captivate]]'
- - Ace
  - '[[SRD-Horn Drill|Horn Drill]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Lovely Kiss|Lovely Kiss]]'
- - Pro
  - '[[SRD-Morning Sun|Morning Sun]]'
- - Pro
  - '[[SRD-Smart Strike|Smart Strike]]'
Number: 33
ShuffleToken: SRD-nidorino-ShuffleToken.png
Type1: Poison
Type2: ''
Weight:
  Kilograms: 19.5
  Pounds: 43.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-nidorino-BookSprite.png|wsmall]]
> ![[SRD-nidorino-HomeSprite.png]]
> ![[SRD-nidorino-BoxSprite.png|htiny]]
> ![[SRD-nidorino-ShuffleToken.png|wsmall]]


*Poison Pin Pokemon*
*An independent and fierce creature. It roams alone in search for a mate and will compete with other males around. It will violently charge with a venom drenched horn against intruders.*

**DexID**:: 0033
**Name**:: Nidorino
**Type**:: Poison
**Abilities**:: [[SRD-Poison Point|Poison Point]] / [[SRD-Rivalry|Rivalry]] ([[SRD-Hustle|Hustle]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'0" / 0.9m
**Weight**: 43.0lbs / 19.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   | Item       |
|:----------|:------------------|:-------|:--------|:-----------|
| From      | [[SRD-Nidoran M]] | Level  | Medium  |            |
| To        | [[SRD-Nidoking]]  | Stone  |         | Moon Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Nidorino.md"
flatten moves as T
where file.path = this.file.path
```
