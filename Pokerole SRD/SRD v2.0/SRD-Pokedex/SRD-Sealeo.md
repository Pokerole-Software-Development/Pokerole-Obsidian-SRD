---
Ability1: Thick Fat
Ability2: Ice Body
BookSprite: SRD-sealeo-BookSprite.png
BoxSprite: SRD-sealeo-BoxSprite.png
DexCategory: Ball Roll Pokemon
DexDescription: "They play with the Spheal in the herd by spinning them with their\
  \ noses. When they are not in the wild they\u2019ll spin almost any round object,\
  \ even Pokeballs. Sealeos are great hunters underwater."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Spheal]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Walrein]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Oblivious
HomeSprite: SRD-sealeo-HomeSprite.png
Image: sealeo.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Powder Snow|Powder Snow]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - Beginner
  - '[[SRD-Encore|Encore]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ice Ball|Ice Ball]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Aurora Beam|Aurora Beam]]'
- - Amateur
  - '[[SRD-Hail|Hail]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Rest|Rest]]'
- - Ace
  - '[[SRD-Snore|Snore]]'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - Ace
  - '[[SRD-Sheer Cold|Sheer Cold]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Pro
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Pro
  - '[[SRD-Super Fang|Super Fang]]'
Number: 364
ShuffleToken: SRD-sealeo-ShuffleToken.png
Type1: Ice
Type2: Water
Weight:
  Kilograms: 87.6
  Pounds: 193.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-sealeo-BookSprite.png|wsmall]]
> ![[SRD-sealeo-HomeSprite.png]]
> ![[SRD-sealeo-BoxSprite.png|htiny]]
> ![[SRD-sealeo-ShuffleToken.png|wsmall]]


*Ball Roll Pokemon*
*They play with the Spheal in the herd by spinning them with their noses. When they are not in the wild they’ll spin almost any round object, even Pokeballs. Sealeos are great hunters underwater.*

**DexID**:: 0364
**Name**:: Sealeo
**Type**:: Ice / Water
**Abilities**:: [[SRD-Thick Fat|Thick Fat]] / [[SRD-Ice Body|Ice Body]] ([[SRD-Oblivious|Oblivious]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'6" / 1.1m
**Weight**: 193.1lbs / 87.6kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Spheal]]  | Level  | Medium  |
| To        | [[SRD-Walrein]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Sealeo.md"
flatten moves as T
where file.path = this.file.path
```
