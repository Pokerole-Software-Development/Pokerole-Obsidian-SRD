---
Ability1: Keen Eye
Ability2: Tangled Feet
BookSprite: SRD-pidgeot-BookSprite.png
BoxSprite: SRD-pidgeot-BoxSprite.png
DexCategory: Bird Pokemon
DexDescription: "This Pokemon\u2019s plumage is made of beautiful glossy feathers.\
  \ Pidgeot is an excellent hunter with well developed wing muscles that make it strong\
  \ enough to whip up a gusty windstorm with just a few flaps."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Pidgeotto]]'
  Speed: Medium
- Evolves: To
  Item: Pidgeotite
  Kind: Mega
  Pokemon: '[[SRD-Pidgeot (Mega Form)]]'
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Big Pecks
HomeSprite: SRD-pidgeot-HomeSprite.png
Image: pidgeot.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sand Attack|Sand Attack]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Twister|Twister]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Gust|Gust]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Whirlwind|Whirlwind]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ominous Wind|Ominous Wind]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Feather Dance|Feather Dance]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Agility|Agility]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wing Attack|Wing Attack]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mirror Move|Mirror Move]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Roost|Roost]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tailwind|Tailwind]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Heat Wave|Heat Wave]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hurricane|Hurricane]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Reflect|Reflect]]'
Number: 18
ShuffleToken: SRD-pidgeot-ShuffleToken.png
Type1: Normal
Type2: Flying
Weight:
  Kilograms: 39.5
  Pounds: 87.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-pidgeot-BookSprite.png|wsmall]]
> ![[SRD-pidgeot-HomeSprite.png]]
> ![[SRD-pidgeot-BoxSprite.png|htiny]]
> ![[SRD-pidgeot-ShuffleToken.png|wsmall]]


*Bird Pokemon*
*This Pokemon’s plumage is made of beautiful glossy feathers. Pidgeot is an excellent hunter with well developed wing muscles that make it strong enough to whip up a gusty windstorm with just a few flaps.*

**DexID**:: 0018
**Name**:: Pidgeot
**Type**:: Normal / Flying
**Abilities**:: [[SRD-Keen Eye|Keen Eye]] / [[SRD-Tangled Feet|Tangled Feet]] ([[SRD-Big Pecks|Big Pecks]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'9" / 1.5m
**Weight**: 87.1lbs / 39.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon                     | Kind   | Speed   | Item       |
|:----------|:----------------------------|:-------|:--------|:-----------|
| From      | [[SRD-Pidgeotto]]           | Level  | Medium  |            |
| To        | [[SRD-Pidgeot (Mega Form)]] | Mega   |         | Pidgeotite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Pidgeot.md"
flatten moves as T
where file.path = this.file.path
```
