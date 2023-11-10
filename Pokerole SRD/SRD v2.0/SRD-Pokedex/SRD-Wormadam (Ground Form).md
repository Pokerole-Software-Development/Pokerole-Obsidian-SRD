---
Ability1: Speed Boost
Ability2: Compound Eyes
BookSprite: SRD-wormadam-ground-form-BookSprite.png
BoxSprite: SRD-wormadam-ground-form-BoxSprite.png
DexCategory: Bagworm Pokemon
DexDescription: When Burmy evolved, its Sand cloak became a part of its body. For
  this reason there are many variations in body and type. It is a calm Pokemon that
  loves odd-shaped stones. This Pokemon is female only.
EventAbilities: ''
Evolutions:
- Evolves: From
  Gender: Female
  Kind: Level
  Pokemon: '[[SRD-Burmy]]'
  Speed: Fast
GenderType: F
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Overcoat
HomeSprite: SRD-wormadam-ground-form-HomeSprite.png
Image: wormadam-ground-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Protect|Protect]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Captivate|Captivate]]'
- - Amateur
  - '[[SRD-Flail|Flail]]'
- - Amateur
  - '[[SRD-Bug Bite|Bug Bite]]'
- - Amateur
  - '[[SRD-Hidden Power|Hidden Power]]'
- - Amateur
  - '[[SRD-Confusion|Confusion]]'
- - Amateur
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Amateur
  - '[[SRD-Harden|Harden]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Quiver Dance|Quiver Dance]]'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Ace
  - '[[SRD-Attract|Attract]]'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Fissure|Fissure]]'
- - Ace
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Synthesis|Synthesis]]'
- - Pro
  - '[[SRD-Electroweb|Electroweb]]'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
Number: 413
ShuffleToken: SRD-wormadam-ground-form-ShuffleToken.png
Type1: Bug
Type2: Ground
Weight:
  Kilograms: 6.5
  Pounds: 14.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-wormadam-ground-form-BookSprite.png|wsmall]]
> ![[SRD-wormadam-ground-form-HomeSprite.png]]
> ![[SRD-wormadam-ground-form-BoxSprite.png|htiny]]
> ![[SRD-wormadam-ground-form-ShuffleToken.png|wsmall]]


*Bagworm Pokemon*
*When Burmy evolved, its Sand cloak became a part of its body. For this reason there are many variations in body and type. It is a calm Pokemon that loves odd-shaped stones. This Pokemon is female only.*

**DexID**:: 0413F2
**Name**:: Wormadam (Ground Form)
**Type**:: Bug / Ground
**Abilities**:: [[SRD-Speed Boost|Speed Boost]] / [[SRD-Compound Eyes|Compound Eyes]] ([[SRD-Overcoat|Overcoat]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 1'6" / 0.5m
**Weight**: 14.3lbs / 6.5kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon       | Kind   | Speed   | Gender   |
|:----------|:--------------|:-------|:--------|:---------|
| From      | [[SRD-Burmy]] | Level  | Fast    | Female   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Wormadam (Ground Form).md"
flatten moves as T
where file.path = this.file.path
```
