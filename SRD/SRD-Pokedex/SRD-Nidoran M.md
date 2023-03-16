---
Ability1: Poison Point
Ability2: Rivalry
BookSprite: SRD-nidoran-m-BookSprite.png
BoxSprite: SRD-nidoran-m-BoxSprite.png
DexCategory: Poison Pin Pokemon
DexDescription: "The male Nidoran has developed a great alertness to sounds. Its small\
  \ body is covered in spikes that are drenched in venom when he\u2019s threatened.\
  \ He will defend his mate and home fiercely."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Nidorino]]'
  Speed: Medium
GenderType: M
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Hustle
HomeSprite: SRD-nidoran-m-HomeSprite.png
Image: nidoran-m.png
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
  - '[[SRD-Confusion|Confusion]]'
Number: 32
ShuffleToken: SRD-nidoran-m-ShuffleToken.png
Type1: Poison
Type2: ''
Weight:
  Kilograms: 9.0
  Pounds: 19.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-nidoran-m-BookSprite.png|wsmall]]
> ![[SRD-nidoran-m-HomeSprite.png]]
> ![[SRD-nidoran-m-BoxSprite.png|htiny]]
> ![[SRD-nidoran-m-ShuffleToken.png|wsmall]]


*Poison Pin Pokemon*
*The male Nidoran has developed a great alertness to sounds. Its small body is covered in spikes that are drenched in venom when he’s threatened. He will defend his mate and home fiercely.*

**DexID**:: 0032
**Name**:: Nidoran M
**Type**:: Poison
**Abilities**:: [[SRD-Poison Point|Poison Point]] / [[SRD-Rivalry|Rivalry]] ([[SRD-Hustle|Hustle]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'6" / 0.5m
**Weight**: 19.8lbs / 9.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Nidorino]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Nidoran M.md"
flatten moves as T
where file.path = this.file.path
```
