---
Ability1: Static
Ability2: Lightning Rod
BookSprite: SRD-electrike-BookSprite.png
BoxSprite: SRD-electrike-BoxSprite.png
DexCategory: Lightning Pokemon
DexDescription: Their fur stores electricity, leaving a trail of sparks as they run.
  By stimulating their legs with voltage, Electrike's speed and power is greatly increased.
  They are not very common, though.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Manectric]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Minus
HomeSprite: SRD-electrike-HomeSprite.png
Image: electrike.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Beginner
  - '[[SRD-Howl|Howl]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[SRD-Spark|Spark]]'
- - Amateur
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - Ace
  - '[[SRD-Charge|Charge]]'
- - Ace
  - '[[SRD-Wild Charge|Wild Charge]]'
- - Ace
  - '[[SRD-Thunder|Thunder]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Pro
  - '[[SRD-Eerie Impulse|Eerie Impulse]]'
- - Pro
  - '[[SRD-Crunch|Crunch]]'
Number: 309
ShuffleToken: SRD-electrike-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 15.2
  Pounds: 33.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-electrike-BookSprite.png|wsmall]]
> ![[SRD-electrike-HomeSprite.png]]
> ![[SRD-electrike-BoxSprite.png|htiny]]
> ![[SRD-electrike-ShuffleToken.png|wsmall]]


*Lightning Pokemon*
*Their fur stores electricity, leaving a trail of sparks as they run. By stimulating their legs with voltage, Electrike's speed and power is greatly increased. They are not very common, though.*

**DexID**:: 0309
**Name**:: Electrike
**Type**:: Electric
**Abilities**:: [[SRD-Static|Static]] / [[SRD-Lightning Rod|Lightning Rod]] ([[SRD-Minus|Minus]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'0" / 0.6m
**Weight**: 33.5lbs / 15.2kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Manectric]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Electrike.md"
flatten moves as T
where file.path = this.file.path
```
