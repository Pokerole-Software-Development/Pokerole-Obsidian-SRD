---
Ability1: Rough Skin
Ability2: ''
BookSprite: SRD-carvanha-BookSprite.png
BoxSprite: SRD-carvanha-BoxSprite.png
DexCategory: Savage Pokemon
DexDescription: Anything near a Carvanha school will be swarmed, attacked and tore
  to bits. However, they are very timid when they are on their own. They live in rivers
  in the jungle and dislike salt water.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Sharpedo]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Speed Boost
HomeSprite: SRD-carvanha-HomeSprite.png
Image: carvanha.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Bite|Bite]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Rage|Rage]]'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Poison Fang|Poison Fang]]'
- - Ace
  - '[[SRD-Agility|Agility]]'
- - Ace
  - '[[SRD-Assurance|Assurance]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Super Fang|Super Fang]]'
- - Pro
  - '[[SRD-Dive|Dive]]'
- - Pro
  - '[[SRD-Bounce|Bounce]]'
Number: 318
ShuffleToken: SRD-carvanha-ShuffleToken.png
Type1: Water
Type2: Dark
Weight:
  Kilograms: 20.8
  Pounds: 45.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-carvanha-BookSprite.png|wsmall]]
> ![[SRD-carvanha-HomeSprite.png]]
> ![[SRD-carvanha-BoxSprite.png|htiny]]
> ![[SRD-carvanha-ShuffleToken.png|wsmall]]


*Savage Pokemon*
*Anything near a Carvanha school will be swarmed, attacked and tore to bits. However, they are very timid when they are on their own. They live in rivers in the jungle and dislike salt water.*

**DexID**:: 0318
**Name**:: Carvanha
**Type**:: Water / Dark
**Abilities**:: [[SRD-Rough Skin|Rough Skin]] ([[SRD-Speed Boost|Speed Boost]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'6" / 0.8m
**Weight**: 45.9lbs / 20.8kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Sharpedo]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Carvanha.md"
flatten moves as T
where file.path = this.file.path
```
