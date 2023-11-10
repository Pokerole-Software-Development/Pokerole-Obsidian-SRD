---
Ability1: Torrent
Ability2: ''
BookSprite: SRD-primarina-BookSprite.png
BoxSprite: SRD-primarina-BoxSprite.png
DexCategory: Soloist Pokemon
DexDescription: "All modern Primarina sing a song that has been passed down through\
  \ generations. Legend says that you can hear their true song when you are in the\
  \ deep of the sea. Make sure its throat doesn\u2019t get sore."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Brionne]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 5.9
  Meters: 1.8
HiddenAbility: Liquid Voice
HomeSprite: SRD-primarina-HomeSprite.png
Image: primarina.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - Starter
  - '[[SRD-Pound|Pound]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-Baby-Doll Eyes|Baby-Doll Eyes]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Amateur
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - Amateur
  - '[[SRD-Encore|Encore]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Sing|Sing]]'
- - Amateur
  - '[[SRD-Double Slap|Double Slap]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sparkling Aria|Sparkling Aria]]'
- - Ace
  - '[[SRD-Moonblast|Moonblast]]'
- - Ace
  - '[[SRD-Captivate|Captivate]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Misty Terrain|Misty Terrain]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Perish Song|Perish Song]]'
- - Pro
  - '[[SRD-Amnesia|Amnesia]]'
- - Pro
  - '[[SRD-Misty Terrain|Misty Terrain]]'
Number: 730
ShuffleToken: SRD-primarina-ShuffleToken.png
Type1: Water
Type2: Fairy
Weight:
  Kilograms: 44.0
  Pounds: 97.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-primarina-BookSprite.png|wsmall]]
> ![[SRD-primarina-HomeSprite.png]]
> ![[SRD-primarina-BoxSprite.png|htiny]]
> ![[SRD-primarina-ShuffleToken.png|wsmall]]


*Soloist Pokemon*
*All modern Primarina sing a song that has been passed down through generations. Legend says that you can hear their true song when you are in the deep of the sea. Make sure its throat doesn’t get sore.*

**DexID**:: 0730
**Name**:: Primarina
**Type**:: Water / Fairy
**Abilities**:: [[SRD-Torrent|Torrent]] ([[SRD-Liquid Voice|Liquid Voice]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 5'9" / 1.8m
**Weight**: 97.0lbs / 44.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Brionne]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Primarina.md"
flatten moves as T
where file.path = this.file.path
```
