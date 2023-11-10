---
Ability1: Shield Dust
Ability2: ''
BookSprite: SRD-dustox-BookSprite.png
BoxSprite: SRD-dustox-BoxSprite.png
DexCategory: Poison Moth Pokemon
DexDescription: They travel in big groups during the night, attracted to bright lights
  and big cities. Their flight releases a poisonous shining dust that causes mayhem
  in towns. For this reason people dislike them.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Cascoon]]'
  Speed: Fast
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Compound Eyes
HomeSprite: SRD-dustox-HomeSprite.png
Image: dustox.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Confusion|Confusion]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Gust|Gust]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Moonlight|Moonlight]]'
- - Amateur
  - '[[SRD-Venoshock|Venoshock]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Amateur
  - '[[SRD-Light Screen|Light Screen]]'
- - Amateur
  - '[[SRD-Silver Wind|Silver Wind]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Toxic|Toxic]]'
- - Ace
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - Ace
  - '[[SRD-Quiver Dance|Quiver Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Air Cutter|Air Cutter]]'
- - Pro
  - '[[SRD-Swift|Swift]]'
- - Pro
  - '[[SRD-Twister|Twister]]'
Number: 269
ShuffleToken: SRD-dustox-ShuffleToken.png
Type1: Bug
Type2: Poison
Weight:
  Kilograms: 31.6
  Pounds: 69.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-dustox-BookSprite.png|wsmall]]
> ![[SRD-dustox-HomeSprite.png]]
> ![[SRD-dustox-BoxSprite.png|htiny]]
> ![[SRD-dustox-ShuffleToken.png|wsmall]]


*Poison Moth Pokemon*
*They travel in big groups during the night, attracted to bright lights and big cities. Their flight releases a poisonous shining dust that causes mayhem in towns. For this reason people dislike them.*

**DexID**:: 0269
**Name**:: Dustox
**Type**:: Bug / Poison
**Abilities**:: [[SRD-Shield Dust|Shield Dust]] ([[SRD-Compound Eyes|Compound Eyes]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'9" / 1.2m
**Weight**: 69.7lbs / 31.6kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Cascoon]] | Level  | Fast    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Dustox.md"
flatten moves as T
where file.path = this.file.path
```
