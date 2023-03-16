---
Ability1: Wonder Skin
Ability2: Magic Guard
BookSprite: SRD-sigilyph-BookSprite.png
BoxSprite: SRD-sigilyph-BoxSprite.png
DexCategory: Avianoid Pokemon
DexDescription: It is known that they worked as guards for an ancient civilization
  and a few can still be seen patrolling its borders, following the same route for
  centuries. They attack people that sneak through their barriers.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: Tinted Lens
HomeSprite: SRD-sigilyph-HomeSprite.png
Image: sigilyph.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Gust|Gust]]'
- - Starter
  - '[[SRD-Miracle Eye|Miracle Eye]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Beginner
  - '[[SRD-Psywave|Psywave]]'
- - Beginner
  - '[[SRD-Tailwind|Tailwind]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Air Cutter|Air Cutter]]'
- - Amateur
  - '[[SRD-Light Screen|Light Screen]]'
- - Amateur
  - '[[SRD-Reflect|Reflect]]'
- - Amateur
  - '[[SRD-Gravity|Gravity]]'
- - Amateur
  - '[[SRD-Mirror Move|Mirror Move]]'
- - Amateur
  - '[[SRD-Psychic|Psychic]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Air Slash|Air Slash]]'
- - Ace
  - '[[SRD-Synchronoise|Synchronoise]]'
- - Ace
  - '[[SRD-Cosmic Power|Cosmic Power]]'
- - Ace
  - '[[SRD-Sky Attack|Sky Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Stored Power|Stored Power]]'
- - Pro
  - '[[SRD-Telekinesis|Telekinesis]]'
- - Pro
  - '[[SRD-Psycho Shift|Psycho Shift]]'
Number: 561
ShuffleToken: SRD-sigilyph-ShuffleToken.png
Type1: Psychic
Type2: Flying
Weight:
  Kilograms: 14.0
  Pounds: 30.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-sigilyph-BookSprite.png|wsmall]]
> ![[SRD-sigilyph-HomeSprite.png]]
> ![[SRD-sigilyph-BoxSprite.png|htiny]]
> ![[SRD-sigilyph-ShuffleToken.png|wsmall]]


*Avianoid Pokemon*
*It is known that they worked as guards for an ancient civilization and a few can still be seen patrolling its borders, following the same route for centuries. They attack people that sneak through their barriers.*

**DexID**:: 0561
**Name**:: Sigilyph
**Type**:: Psychic / Flying
**Abilities**:: [[SRD-Wonder Skin|Wonder Skin]] / [[SRD-Magic Guard|Magic Guard]] ([[SRD-Tinted Lens|Tinted Lens]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'6" / 1.4m
**Weight**: 30.9lbs / 14.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Sigilyph.md"
flatten moves as T
where file.path = this.file.path
```
