---
Ability1: Refrigerate
Ability2: ''
BookSprite: SRD-amaura-BookSprite.png
BoxSprite: SRD-amaura-BoxSprite.png
DexCategory: Tundra Pokemon
DexDescription: "This ancient Pokemon was restored from part of its body that had\
  \ been frozen for over 100 million years. This calm Pokemon lived in the cold lands\
  \ where violent predators like Tyrantrum couldn\u2019t reach it."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Aurorus]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: Snow Warning
HomeSprite: SRD-amaura-HomeSprite.png
Image: amaura.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Powder Snow|Powder Snow]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Beginner
  - '[[SRD-Rock Throw|Rock Throw]]'
- - Beginner
  - '[[SRD-Icy Wind|Icy Wind]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Mist|Mist]]'
- - Amateur
  - '[[SRD-Aurora Beam|Aurora Beam]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Round|Round]]'
- - Amateur
  - '[[SRD-Avalanche|Avalanche]]'
- - Amateur
  - '[[SRD-Hail|Hail]]'
- - Amateur
  - '[[SRD-Nature Power|Nature Power]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Encore|Encore]]'
- - Ace
  - '[[SRD-Light Screen|Light Screen]]'
- - Ace
  - '[[SRD-Ice Beam|Ice Beam]]'
- - Ace
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Earth Power|Earth Power]]'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Pro
  - '[[SRD-Water Pulse|Water Pulse]]'
Number: 698
ShuffleToken: SRD-amaura-ShuffleToken.png
Type1: Rock
Type2: Ice
Weight:
  Kilograms: 25.2
  Pounds: 55.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-amaura-BookSprite.png|wsmall]]
> ![[SRD-amaura-HomeSprite.png]]
> ![[SRD-amaura-BoxSprite.png|htiny]]
> ![[SRD-amaura-ShuffleToken.png|wsmall]]


*Tundra Pokemon*
*This ancient Pokemon was restored from part of its body that had been frozen for over 100 million years. This calm Pokemon lived in the cold lands where violent predators like Tyrantrum couldn’t reach it.*

**DexID**:: 0698
**Name**:: Amaura
**Type**:: Rock / Ice
**Abilities**:: [[SRD-Refrigerate|Refrigerate]] ([[SRD-Snow Warning|Snow Warning]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 4'3" / 1.3m
**Weight**: 55.6lbs / 25.2kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Aurorus]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Amaura.md"
flatten moves as T
where file.path = this.file.path
```
