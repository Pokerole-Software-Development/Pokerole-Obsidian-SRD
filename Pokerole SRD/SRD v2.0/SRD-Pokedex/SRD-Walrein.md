---
Ability1: Thick Fat
Ability2: Ice Body
BookSprite: SRD-walrein-BookSprite.png
BoxSprite: SRD-walrein-BoxSprite.png
DexCategory: Ice Break Pokemon
DexDescription: The leader of the herd is a powerful Walrein. They are very aggressive
  and will protect their herd even at the cost of their lives. Their tusks can shatter
  giant blocks of ice. It is relentless and unpredictable.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Sealeo]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: Oblivious
HomeSprite: SRD-walrein-HomeSprite.png
Image: walrein.png
Legendary: 'No'
Moves:
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
  - '[[SRD-Crunch|Crunch]]'
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
- - Amateur
  - '[[SRD-Ice Fang|Ice Fang]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Snore|Snore]]'
- - Ace
  - '[[SRD-Sheer Cold|Sheer Cold]]'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - Ace
  - '[[SRD-Rest|Rest]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Belly Drum|Belly Drum]]'
- - Pro
  - '[[SRD-Fissure|Fissure]]'
- - Pro
  - '[[SRD-Aqua Tail|Aqua Tail]]'
Number: 365
ShuffleToken: SRD-walrein-ShuffleToken.png
Type1: Ice
Type2: Water
Weight:
  Kilograms: 150.6
  Pounds: 332.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-walrein-BookSprite.png|wsmall]]
> ![[SRD-walrein-HomeSprite.png]]
> ![[SRD-walrein-BoxSprite.png|htiny]]
> ![[SRD-walrein-ShuffleToken.png|wsmall]]


*Ice Break Pokemon*
*The leader of the herd is a powerful Walrein. They are very aggressive and will protect their herd even at the cost of their lives. Their tusks can shatter giant blocks of ice. It is relentless and unpredictable.*

**DexID**:: 0365
**Name**:: Walrein
**Type**:: Ice / Water
**Abilities**:: [[SRD-Thick Fat|Thick Fat]] / [[SRD-Ice Body|Ice Body]] ([[SRD-Oblivious|Oblivious]])
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'6" / 1.4m
**Weight**: 332.0lbs / 150.6kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Sealeo]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Walrein.md"
flatten moves as T
where file.path = this.file.path
```
