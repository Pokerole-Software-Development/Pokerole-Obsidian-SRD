---
Ability1: Inner Focus
Ability2: ''
BookSprite: SRD-golbat-BookSprite.png
BoxSprite: SRD-golbat-BoxSprite.png
DexCategory: Bat Pokemon
DexDescription: A stealthy Pokemon who loves the dark. Its fangs can puncture even
  a thick hide. It loves to feast on the blood of people and Pokemon alike. If it
  drinks too much, it gets heavy and can hardly fly.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Zubat]]'
  Speed: Medium
- Evolves: To
  Kind: Stat
  Pokemon: '[[SRD-Crobat]]'
  Stat: Happiness
  Value: 4
GenderType: ''
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: Infiltrator
HomeSprite: SRD-golbat-HomeSprite.png
Image: golbat.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Absorb|Absorb]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Wing Attack|Wing Attack]]'
- - Beginner
  - '[[SRD-Supersonic|Supersonic]]'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Air Cutter|Air Cutter]]'
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - Amateur
  - '[[SRD-Poison Fang|Poison Fang]]'
- - Amateur
  - '[[SRD-Mean Look|Mean Look]]'
- - Amateur
  - '[[SRD-Leech Life|Leech Life]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Acrobatics|Acrobatics]]'
- - Ace
  - '[[SRD-Haze|Haze]]'
- - Ace
  - '[[SRD-Venoshock|Venoshock]]'
- - Ace
  - '[[SRD-Air Slash|Air Slash]]'
- - Ace
  - '[[SRD-Quick Guard|Quick Guard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Pro
  - '[[SRD-Super Fang|Super Fang]]'
- - Pro
  - '[[SRD-Venom Drench|Venom Drench]]'
Number: 42
ShuffleToken: SRD-golbat-ShuffleToken.png
Type1: Poison
Type2: Flying
Weight:
  Kilograms: 55.0
  Pounds: 121.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-golbat-BookSprite.png|wsmall]]
> ![[SRD-golbat-HomeSprite.png]]
> ![[SRD-golbat-BoxSprite.png|htiny]]
> ![[SRD-golbat-ShuffleToken.png|wsmall]]


*Bat Pokemon*
*A stealthy Pokemon who loves the dark. Its fangs can puncture even a thick hide. It loves to feast on the blood of people and Pokemon alike. If it drinks too much, it gets heavy and can hardly fly.*

**DexID**:: 0042
**Name**:: Golbat
**Type**:: Poison / Flying
**Abilities**:: [[SRD-Inner Focus|Inner Focus]] ([[SRD-Infiltrator|Infiltrator]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'2" / 1.6m
**Weight**: 121.3lbs / 55.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   | Stat      | Value   |
|:----------|:---------------|:-------|:--------|:----------|:--------|
| From      | [[SRD-Zubat]]  | Level  | Medium  |           |         |
| To        | [[SRD-Crobat]] | Stat   |         | Happiness | 4.0     |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Golbat.md"
flatten moves as T
where file.path = this.file.path
```
