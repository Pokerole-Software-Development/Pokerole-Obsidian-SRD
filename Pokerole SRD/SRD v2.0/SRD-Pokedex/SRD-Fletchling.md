---
Ability1: Big Pecks
Ability2: ''
BookSprite: SRD-fletchling-BookSprite.png
BoxSprite: SRD-fletchling-BoxSprite.png
DexCategory: Tiny Robin Pokemon
DexDescription: These cute Pokemon send signals to one another with beautiful chirps
  and feather movements. But despite the beauty of its lilting voice it is merciless
  to intruders that come close to its nest.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Fletchinder]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Gale Wings
HomeSprite: SRD-fletchling-HomeSprite.png
Image: fletchling.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Peck|Peck]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Flail|Flail]]'
- - Amateur
  - '[[SRD-Roost|Roost]]'
- - Amateur
  - '[[SRD-Razor Wind|Razor Wind]]'
- - Amateur
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Amateur
  - '[[SRD-Flame Charge|Flame Charge]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Acrobatics|Acrobatics]]'
- - Ace
  - '[[SRD-Me First|Me First]]'
- - Ace
  - '[[SRD-Tailwind|Tailwind]]'
- - Ace
  - '[[SRD-Steel Wing|Steel Wing]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Snatch|Snatch]]'
- - Pro
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Pro
  - '[[SRD-Air Cutter|Air Cutter]]'
Number: 661
ShuffleToken: SRD-fletchling-ShuffleToken.png
Type1: Normal
Type2: Flying
Weight:
  Kilograms: 1.7
  Pounds: 3.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-fletchling-BookSprite.png|wsmall]]
> ![[SRD-fletchling-HomeSprite.png]]
> ![[SRD-fletchling-BoxSprite.png|htiny]]
> ![[SRD-fletchling-ShuffleToken.png|wsmall]]


*Tiny Robin Pokemon*
*These cute Pokemon send signals to one another with beautiful chirps and feather movements. But despite the beauty of its lilting voice it is merciless to intruders that come close to its nest.*

**DexID**:: 0661
**Name**:: Fletchling
**Type**:: Normal / Flying
**Abilities**:: [[SRD-Big Pecks|Big Pecks]] ([[SRD-Gale Wings|Gale Wings]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 3.7lbs / 1.7kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon             | Kind   | Speed   |
|:----------|:--------------------|:-------|:--------|
| To        | [[SRD-Fletchinder]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Fletchling.md"
flatten moves as T
where file.path = this.file.path
```
