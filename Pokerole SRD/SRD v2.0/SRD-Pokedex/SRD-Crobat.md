---
Ability1: Inner Focus
Ability2: ''
BookSprite: SRD-crobat-BookSprite.png
BoxSprite: SRD-crobat-BoxSprite.png
DexCategory: Bat Pokemon
DexDescription: Very rare in the wild. People have called it a vampire. It sneaks
  up on its intended prey using wings that barely make a sound. Crobat is a surprisingly
  loyal Pokemon.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Stat
  Pokemon: '[[SRD-Golbat]]'
  Stat: Happiness
  Value: 4
GenderType: ''
Height:
  Feet: 5.9
  Meters: 1.8
HiddenAbility: Infiltrator
HomeSprite: SRD-crobat-HomeSprite.png
Image: crobat.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Absorb|Absorb]]'
- - Starter
  - '[[SRD-Screech|Screech]]'
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - Starter
  - '[[SRD-Supersonic|Supersonic]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Wing Attack|Wing Attack]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Acrobatics|Acrobatics]]'
- - Amateur
  - '[[SRD-Air Cutter|Air Cutter]]'
- - Amateur
  - '[[SRD-Mean Look|Mean Look]]'
- - Amateur
  - '[[SRD-Leech Life|Leech Life]]'
- - Amateur
  - '[[SRD-Poison Fang|Poison Fang]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Cross Poison|Cross Poison]]'
- - Ace
  - '[[SRD-Haze|Haze]]'
- - Ace
  - '[[SRD-Air Slash|Air Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Brave Bird|Brave Bird]]'
- - Pro
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Pro
  - '[[SRD-Heat Wave|Heat Wave]]'
Number: 169
ShuffleToken: SRD-crobat-ShuffleToken.png
Type1: Poison
Type2: Flying
Weight:
  Kilograms: 75.0
  Pounds: 165.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-crobat-BookSprite.png|wsmall]]
> ![[SRD-crobat-HomeSprite.png]]
> ![[SRD-crobat-BoxSprite.png|htiny]]
> ![[SRD-crobat-ShuffleToken.png|wsmall]]


*Bat Pokemon*
*Very rare in the wild. People have called it a vampire. It sneaks up on its intended prey using wings that barely make a sound. Crobat is a surprisingly loyal Pokemon.*

**DexID**:: 0169
**Name**:: Crobat
**Type**:: Poison / Flying
**Abilities**:: [[SRD-Inner Focus|Inner Focus]] ([[SRD-Infiltrator|Infiltrator]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'9" / 1.8m
**Weight**: 165.3lbs / 75.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon        | Kind   | Stat      |   Value |
|:----------|:---------------|:-------|:----------|--------:|
| From      | [[SRD-Golbat]] | Stat   | Happiness |       4 |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Crobat.md"
flatten moves as T
where file.path = this.file.path
```
