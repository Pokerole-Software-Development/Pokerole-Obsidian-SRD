---
Ability1: Intimidate
Ability2: ''
BookSprite: SRD-masquerain-BookSprite.png
BoxSprite: SRD-masquerain-BoxSprite.png
DexCategory: Eyeball Pokemon
DexDescription: "Their antennas look like terrifying eyes. Masquerains can fly in\
  \ any direction like a helicopter, but their wings are soft and fragile, so they\
  \ can\u2019t fly when it\u2019s raining. They cling to trees at night to sleep."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Surskit]]'
  Speed: Fast
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Unnerve
HomeSprite: SRD-masquerain-HomeSprite.png
Image: masquerain.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Bubble|Bubble]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ominous Wind|Ominous Wind]]'
- - Amateur
  - '[[SRD-Quiver Dance|Quiver Dance]]'
- - Amateur
  - '[[SRD-Stun Spore|Stun Spore]]'
- - Amateur
  - '[[SRD-Water Sport|Water Sport]]'
- - Amateur
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Amateur
  - '[[SRD-Air Cutter|Air Cutter]]'
- - Amateur
  - '[[SRD-Gust|Gust]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - Ace
  - '[[SRD-Silver Wind|Silver Wind]]'
- - Ace
  - '[[SRD-Air Slash|Air Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fell Stinger|Fell Stinger]]'
- - Pro
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Pro
  - '[[SRD-Psybeam|Psybeam]]'
Number: 284
ShuffleToken: SRD-masquerain-ShuffleToken.png
Type1: Bug
Type2: Flying
Weight:
  Kilograms: 3.6
  Pounds: 7.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-masquerain-BookSprite.png|wsmall]]
> ![[SRD-masquerain-HomeSprite.png]]
> ![[SRD-masquerain-BoxSprite.png|htiny]]
> ![[SRD-masquerain-ShuffleToken.png|wsmall]]


*Eyeball Pokemon*
*Their antennas look like terrifying eyes. Masquerains can fly in any direction like a helicopter, but their wings are soft and fragile, so they can’t fly when it’s raining. They cling to trees at night to sleep.*

**DexID**:: 0284
**Name**:: Masquerain
**Type**:: Bug / Flying
**Abilities**:: [[SRD-Intimidate|Intimidate]] ([[SRD-Unnerve|Unnerve]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'6" / 0.8m
**Weight**: 7.9lbs / 3.6kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Surskit]] | Level  | Fast    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Masquerain.md"
flatten moves as T
where file.path = this.file.path
```
