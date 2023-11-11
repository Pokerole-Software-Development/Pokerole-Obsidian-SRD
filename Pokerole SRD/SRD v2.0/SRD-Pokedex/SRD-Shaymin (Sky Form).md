---
Ability1: Serene Grace
Ability2: ''
BookSprite: SRD-shaymin-sky-form-BookSprite.png
BoxSprite: SRD-shaymin-sky-form-BoxSprite.png
DexCategory: No Data
DexDescription: "There are old traces of gigantic trees that once grew all over the\
  \ earth. They were called the \u201CTrees of Life\u201D and their flowers granted\
  \ the power of flight to the kindhearted, or so the legend says."
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Gracidea flower
  Kind: Special
  Pokemon: '[[SRD-Shaymin]]'
GenderType: N
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: ''
HomeSprite: SRD-shaymin-sky-form-HomeSprite.png
Image: shaymin-sky-form.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Growth|Growth]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Magical Leaf|Magical Leaf]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leech Seed|Leech Seed]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Synthesis|Synthesis]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sweet Scent|Sweet Scent]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Natural Gift|Natural Gift]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Worry Seed|Worry Seed]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Air Slash|Air Slash]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Energy Ball|Energy Ball]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sweet Kiss|Sweet Kiss]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leaf Storm|Leaf Storm]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Seed Flare|Seed Flare]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Endeavor|Endeavor]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Zen Headbutt|Zen Headbutt]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Giga Drain|Giga Drain]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tailwind|Tailwind]]'
Number: 492
ShuffleToken: SRD-shaymin-sky-form-ShuffleToken.png
Type1: Grass
Type2: Flying
Weight:
  Kilograms: 5.2
  Pounds: 11.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-shaymin-sky-form-BookSprite.png|wsmall]]
> ![[SRD-shaymin-sky-form-HomeSprite.png]]
> ![[SRD-shaymin-sky-form-BoxSprite.png|htiny]]
> ![[SRD-shaymin-sky-form-ShuffleToken.png|wsmall]]


*No Data*
*There are old traces of gigantic trees that once grew all over the earth. They were called the “Trees of Life” and their flowers granted the power of flight to the kindhearted, or so the legend says.*

**DexID**:: 0492F1
**Name**:: Shaymin (Sky Form)
**Type**:: Grass / Flying
**Abilities**:: [[SRD-Serene Grace|Serene Grace]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 7)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 1'3" / 0.4m
**Weight**: 11.5lbs / 5.2kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon         | Kind    | Item            |
|:----------|:----------------|:--------|:----------------|
| From      | [[SRD-Shaymin]] | Special | Gracidea flower |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Shaymin (Sky Form).md"
flatten moves as T
where file.path = this.file.path
```
