---
Ability1: Sturdy
Ability2: ''
BookSprite: SRD-forretress-BookSprite.png
BoxSprite: SRD-forretress-BoxSprite.png
DexCategory: Bagworm Pokemon
DexDescription: "It can be found completely rooted to huge tree trunks. It protects\
  \ itself and its tree by scattering spiked pieces from its shell and turning its\
  \ home into a fortress that won\u2019t go down without a fight."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Pineco]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Overcoat
HomeSprite: SRD-forretress-HomeSprite.png
Image: forretress.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Protect|Protect]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bug Bite|Bug Bite]]'
- - Beginner
  - '[[SRD-Self Destruct|Self Destruct]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Toxic Spikes|Toxic Spikes]]'
- - Amateur
  - '[[SRD-Zap Cannon|Zap Cannon]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Amateur
  - '[[SRD-Bide|Bide]]'
- - Amateur
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Amateur
  - '[[SRD-Spikes|Spikes]]'
- - Amateur
  - '[[SRD-Mirror Shot|Mirror Shot]]'
- - Amateur
  - '[[SRD-Autotomize|Autotomize]]'
- - Amateur
  - '[[SRD-Payback|Payback]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Ace
  - '[[SRD-Explosion|Explosion]]'
- - Ace
  - '[[SRD-Heavy Slam|Heavy Slam]]'
- - Ace
  - '[[SRD-Gyro Ball|Gyro Ball]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Pro
  - '[[SRD-Power Trick|Power Trick]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
Number: 205
ShuffleToken: SRD-forretress-ShuffleToken.png
Type1: Bug
Type2: Steel
Weight:
  Kilograms: 125.8
  Pounds: 277.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-forretress-BookSprite.png|wsmall]]
> ![[SRD-forretress-HomeSprite.png]]
> ![[SRD-forretress-BoxSprite.png|htiny]]
> ![[SRD-forretress-ShuffleToken.png|wsmall]]


*Bagworm Pokemon*
*It can be found completely rooted to huge tree trunks. It protects itself and its tree by scattering spiked pieces from its shell and turning its home into a fortress that won’t go down without a fight.*

**DexID**:: 0205
**Name**:: Forretress
**Type**:: Bug / Steel
**Abilities**:: [[SRD-Sturdy|Sturdy]] ([[SRD-Overcoat|Overcoat]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'9" / 1.2m
**Weight**: 277.3lbs / 125.8kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Pineco]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Forretress.md"
flatten moves as T
where file.path = this.file.path
```
