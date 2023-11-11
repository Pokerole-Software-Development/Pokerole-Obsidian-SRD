---
Ability1: Poison Point
Ability2: Rivalry
BookSprite: SRD-nidorina-BookSprite.png
BoxSprite: SRD-nidorina-BoxSprite.png
DexCategory: Poison Pin Pokemon
DexDescription: "Nidorinas are jealous creatures. They don\u2019t like other females\
  \ near their mates. Otherwise, they are very social creatures. When it\u2019s around\
  \ friends or family, its barbs are tucked away to prevent injury."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Nidoran F]]'
  Speed: Medium
- Evolves: To
  Item: Moon Stone
  Kind: Stone
  Pokemon: '[[SRD-Nidoqueen]]'
GenderType: F
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Hustle
HomeSprite: SRD-nidorina-HomeSprite.png
Image: nidorina.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Scratch|Scratch]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Double Kick|Double Kick]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Poison Sting|Poison Sting]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bite|Bite]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Helping Hand|Helping Hand]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Toxic Spikes|Toxic Spikes]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Poison Fang|Poison Fang]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Flatter|Flatter]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Captivate|Captivate]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Crunch|Crunch]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Lovely Kiss|Lovely Kiss]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Moonlight|Moonlight]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Charm|Charm]]'
Number: 30
ShuffleToken: SRD-nidorina-ShuffleToken.png
Type1: Poison
Type2: ''
Weight:
  Kilograms: 20.0
  Pounds: 44.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-nidorina-BookSprite.png|wsmall]]
> ![[SRD-nidorina-HomeSprite.png]]
> ![[SRD-nidorina-BoxSprite.png|htiny]]
> ![[SRD-nidorina-ShuffleToken.png|wsmall]]


*Poison Pin Pokemon*
*Nidorinas are jealous creatures. They don’t like other females near their mates. Otherwise, they are very social creatures. When it’s around friends or family, its barbs are tucked away to prevent injury.*

**DexID**:: 0030
**Name**:: Nidorina
**Type**:: Poison
**Abilities**:: [[SRD-Poison Point|Poison Point]] / [[SRD-Rivalry|Rivalry]] ([[SRD-Hustle|Hustle]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'6" / 0.8m
**Weight**: 44.1lbs / 20.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   | Item       |
|:----------|:------------------|:-------|:--------|:-----------|
| From      | [[SRD-Nidoran F]] | Level  | Medium  |            |
| To        | [[SRD-Nidoqueen]] | Stone  |         | Moon Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Nidorina.md"
flatten moves as T
where file.path = this.file.path
```
