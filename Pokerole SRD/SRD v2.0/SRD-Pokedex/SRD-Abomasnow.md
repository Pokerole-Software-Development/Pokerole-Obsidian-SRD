---
Ability1: Snow Warning
Ability2: ''
BookSprite: SRD-abomasnow-BookSprite.png
BoxSprite: SRD-abomasnow-BoxSprite.png
DexCategory: Frosted Tree Pokemon
DexDescription: "There was a legend for a long time that called this Pokemon \u201C\
  The Ice Monster\u201D. Now we know it is a Pokemon that can cover everything around\
  \ with deep snow. It likes quiet places and only attacks if provoked."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Snover]]'
  Speed: Medium
- Evolves: To
  Item: Abomasite
  Kind: Mega
  Pokemon: '[[SRD-Abomasnow (Mega Form)]]'
GenderType: ''
Height:
  Feet: 7.2
  Meters: 2.2
HiddenAbility: Soundproof
HomeSprite: SRD-abomasnow-HomeSprite.png
Image: abomasnow.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Powder Snow|Powder Snow]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Beginner
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Beginner
  - '[[SRD-Icy Wind|Icy Wind]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Grass Whistle|Grass Whistle]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Mist|Mist]]'
- - Amateur
  - '[[SRD-Ice Shard|Ice Shard]]'
- - Amateur
  - '[[SRD-Ingrain|Ingrain]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Wood Hammer|Wood Hammer]]'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - Ace
  - '[[SRD-Sheer Cold|Sheer Cold]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Growth|Growth]]'
- - Pro
  - '[[SRD-Avalanche|Avalanche]]'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
Number: 460
ShuffleToken: SRD-abomasnow-ShuffleToken.png
Type1: Grass
Type2: Ice
Weight:
  Kilograms: 135.5
  Pounds: 298.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-abomasnow-BookSprite.png|wsmall]]
> ![[SRD-abomasnow-HomeSprite.png]]
> ![[SRD-abomasnow-BoxSprite.png|htiny]]
> ![[SRD-abomasnow-ShuffleToken.png|wsmall]]


*Frosted Tree Pokemon*
*There was a legend for a long time that called this Pokemon “The Ice Monster”. Now we know it is a Pokemon that can cover everything around with deep snow. It likes quiet places and only attacks if provoked.*

**DexID**:: 0460
**Name**:: Abomasnow
**Type**:: Grass / Ice
**Abilities**:: [[SRD-Snow Warning|Snow Warning]] ([[SRD-Soundproof|Soundproof]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 7'2" / 2.2m
**Weight**: 298.7lbs / 135.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon                       | Kind   | Speed   | Item      |
|:----------|:------------------------------|:-------|:--------|:----------|
| From      | [[SRD-Snover]]                | Level  | Medium  |           |
| To        | [[SRD-Abomasnow (Mega Form)]] | Mega   |         | Abomasite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Abomasnow.md"
flatten moves as T
where file.path = this.file.path
```
