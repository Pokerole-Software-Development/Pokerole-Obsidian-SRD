---
Ability1: Thick Fat
Ability2: Huge Power
BookSprite: SRD-marill-BookSprite.png
BoxSprite: SRD-marill-BoxSprite.png
DexCategory: Aquamouse Pokemon
DexDescription: "Marill's tail acts like a floater. Seeing its tail bobbing on the\
  \ water\u2019s surface is a sure indication that this Pokemon is diving to feed\
  \ on algae and aquatic plants. This Pokemon is curious towards humans."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Stat
  Pokemon: '[[SRD-Azurill]]'
  Stat: Happiness
  Value: 4
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Azumarill]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Sap Sipper
HomeSprite: SRD-marill-HomeSprite.png
Image: marill.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Water Sport|Water Sport]]'
- - Beginner
  - '[[SRD-Bubble|Bubble]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Amateur
  - '[[SRD-Rollout|Rollout]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Amateur
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Amateur
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Amateur
  - '[[SRD-Play Rough|Play Rough]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Belly Drum|Belly Drum]]'
- - Pro
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - Pro
  - '[[SRD-Ice Punch|Ice Punch]]'
Number: 183
ShuffleToken: SRD-marill-ShuffleToken.png
Type1: Water
Type2: Fairy
Weight:
  Kilograms: 8.5
  Pounds: 18.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-marill-BookSprite.png|wsmall]]
> ![[SRD-marill-HomeSprite.png]]
> ![[SRD-marill-BoxSprite.png|htiny]]
> ![[SRD-marill-ShuffleToken.png|wsmall]]


*Aquamouse Pokemon*
*Marill's tail acts like a floater. Seeing its tail bobbing on the water’s surface is a sure indication that this Pokemon is diving to feed on algae and aquatic plants. This Pokemon is curious towards humans.*

**DexID**:: 0183
**Name**:: Marill
**Type**:: Water / Fairy
**Abilities**:: [[SRD-Thick Fat|Thick Fat]] / [[SRD-Huge Power|Huge Power]] ([[SRD-Sap Sipper|Sap Sipper]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 18.7lbs / 8.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon           | Kind   | Stat      | Value   | Speed   |
|:----------|:------------------|:-------|:----------|:--------|:--------|
| From      | [[SRD-Azurill]]   | Stat   | Happiness | 4.0     |         |
| To        | [[SRD-Azumarill]] | Level  |           |         | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Marill.md"
flatten moves as T
where file.path = this.file.path
```
