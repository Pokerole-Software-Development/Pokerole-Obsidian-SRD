---
Ability1: Snow Warning
Ability2: ''
BookSprite: SRD-abomasnow-mega-form-BookSprite.png
BoxSprite: SRD-abomasnow-mega-form-BoxSprite.png
DexCategory: Frosted Tree Pokemon
DexDescription: The power of the Mega Stone freezes part of its body creating pointy
  icicles that hail upon its enemies in a blizzard. The angrier it becomes the longer
  the storm will last.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Abomasite
  Kind: Mega
  Pokemon: '[[SRD-Abomasnow]]'
GenderType: ''
Height:
  Feet: 8.9
  Meters: 2.7
HiddenAbility: ''
HomeSprite: SRD-abomasnow-mega-form-HomeSprite.png
Image: abomasnow-mega-form.png
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
ShuffleToken: SRD-abomasnow-mega-form-ShuffleToken.png
Type1: Grass
Type2: Ice
Weight:
  Kilograms: 185.0
  Pounds: 407.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-abomasnow-mega-form-BookSprite.png|wsmall]]
> ![[SRD-abomasnow-mega-form-HomeSprite.png]]
> ![[SRD-abomasnow-mega-form-BoxSprite.png|htiny]]
> ![[SRD-abomasnow-mega-form-ShuffleToken.png|wsmall]]


*Frosted Tree Pokemon*
*The power of the Mega Stone freezes part of its body creating pointy icicles that hail upon its enemies in a blizzard. The angrier it becomes the longer the storm will last.*

**DexID**:: 0460M1
**Name**:: Abomasnow (Mega Form)
**Type**:: Grass / Ice
**Abilities**:: [[SRD-Snow Warning|Snow Warning]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::2) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 8'9" / 2.7m
**Weight**: 407.9lbs / 185.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon           | Kind   | Item      |
|:----------|:------------------|:-------|:----------|
| From      | [[SRD-Abomasnow]] | Mega   | Abomasite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Abomasnow (Mega Form).md"
flatten moves as T
where file.path = this.file.path
```
