---
Ability1: Clear Body
Ability2: Infiltrator
BookSprite: SRD-dreepy-BookSprite.png
BoxSprite: SRD-dreepy-BoxSprite.png
DexCategory: Lingering Pokemon
DexDescription: "After being reborn as a ghost, Dreepy wanders the areas it used to\
  \ inhabit back when it was alive in prehistoric seas. Alone they do not pose much\
  \ of a threat but if they gather in packs you\u2019ll be in trouble."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Drakloak]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Cursed Body
HomeSprite: SRD-dreepy-HomeSprite.png
Image: dreepy.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - Starter
  - '[[SRD-Infestation|Infestation]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Substitute|Substitute]]'
- - Pro
  - '[[SRD-Dragon Tail|Dragon Tail]]'
- - Pro
  - '[[SRD-Double Team|Double Team]]'
Number: 885
ShuffleToken: SRD-dreepy-ShuffleToken.png
Type1: Dragon
Type2: Ghost
Weight:
  Kilograms: 2.0
  Pounds: 4.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-dreepy-BookSprite.png|wsmall]]
> ![[SRD-dreepy-HomeSprite.png]]
> ![[SRD-dreepy-BoxSprite.png|htiny]]
> ![[SRD-dreepy-ShuffleToken.png|wsmall]]


*Lingering Pokemon*
*After being reborn as a ghost, Dreepy wanders the areas it used to inhabit back when it was alive in prehistoric seas. Alone they do not pose much of a threat but if they gather in packs you’ll be in trouble.*

**DexID**:: 0885
**Name**:: Dreepy
**Type**:: Dragon / Ghost
**Abilities**:: [[SRD-Clear Body|Clear Body]] / [[SRD-Infiltrator|Infiltrator]] ([[SRD-Cursed Body|Cursed Body]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'6" / 0.5m
**Weight**: 4.4lbs / 2.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Drakloak]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Dreepy.md"
flatten moves as T
where file.path = this.file.path
```
