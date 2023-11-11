---
Ability1: Dry Skin
Ability2: Sand Veil
BookSprite: SRD-heliolisk-BookSprite.png
BoxSprite: SRD-heliolisk-BoxSprite.png
DexCategory: Generator Pokemon
DexDescription: They flare their frills and generate energy. A single Heliolisk is
  able to generate enough power to light a skyscraper. Due to this, electricity companies
  are investing on breeding and research for this species.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Sun Stone
  Kind: Stone
  Pokemon: '[[SRD-Helioptile]]'
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Solar Power
HomeSprite: SRD-heliolisk-HomeSprite.png
Image: heliolisk.png
Legendary: 'No'
Moves:
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Charge|Charge]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Eerie Impulse|Eerie Impulse]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Razor Wind|Razor Wind]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Parabolic Charge|Parabolic Charge]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Electrify|Electrify]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thunder|Thunder]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Agility|Agility]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hyper Voice|Hyper Voice]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fire Punch|Fire Punch]]'
Number: 695
ShuffleToken: SRD-heliolisk-ShuffleToken.png
Type1: Electric
Type2: Normal
Weight:
  Kilograms: 21.0
  Pounds: 46.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-heliolisk-BookSprite.png|wsmall]]
> ![[SRD-heliolisk-HomeSprite.png]]
> ![[SRD-heliolisk-BoxSprite.png|htiny]]
> ![[SRD-heliolisk-ShuffleToken.png|wsmall]]


*Generator Pokemon*
*They flare their frills and generate energy. A single Heliolisk is able to generate enough power to light a skyscraper. Due to this, electricity companies are investing on breeding and research for this species.*

**DexID**:: 0695
**Name**:: Heliolisk
**Type**:: Electric / Normal
**Abilities**:: [[SRD-Dry Skin|Dry Skin]] / [[SRD-Sand Veil|Sand Veil]] ([[SRD-Solar Power|Solar Power]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'3" / 1.0m
**Weight**: 46.3lbs / 21.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon            | Kind   | Item      |
|:----------|:-------------------|:-------|:----------|
| From      | [[SRD-Helioptile]] | Stone  | Sun Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Heliolisk.md"
flatten moves as T
where file.path = this.file.path
```
