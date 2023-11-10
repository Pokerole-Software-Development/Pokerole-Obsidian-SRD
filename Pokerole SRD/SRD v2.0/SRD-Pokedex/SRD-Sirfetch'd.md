---
Ability1: Steadfast
Ability2: ''
BookSprite: SRD-sirfetchd-BookSprite.png
BoxSprite: SRD-sirfetchd-BoxSprite.png
DexCategory: Wild Duck Pokemon
DexDescription: "Only Farfetch\u2019d that have survived many battles can go thought\
  \ this evolution. They are very proud of their leek spear and leafen shield, When\
  \ this Pokemon's leek withers, it will retire from combat."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Special
  Pokemon: '[[SRD-Farfetch''d (Galarian Form)]]'
  Special: Score 3 Critical hits in 1 battle
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Scrappy
HomeSprite: SRD-sirfetchd-HomeSprite.png
Image: sirfetchd.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Peck|Peck]]'
- - Starter
  - '[[SRD-Sand Attack|Sand Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - Beginner
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Rock Smash|Rock Smash]]'
- - Amateur
  - '[[SRD-Brutal Swing|Brutal Swing]]'
- - Amateur
  - '[[SRD-Detect|Detect]]'
- - Amateur
  - '[[SRD-Knock Off|Knock Off]]'
- - Amateur
  - '[[SRD-Defog|Defog]]'
- - Amateur
  - '[[SRD-Brick Break|Brick Break]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Ace
  - '[[SRD-First Impression|First Impression]]'
- - Ace
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Ace
  - '[[SRD-Leaf Blade|Leaf Blade]]'
- - Ace
  - '[[SRD-Final Gambit|Final Gambit]]'
- - Ace
  - '[[SRD-Brave Bird|Brave Bird]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Meteor Assault|Meteor Assault]]'
- - Pro
  - '[[SRD-Simple Beam|Simple Beam]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
- - Pro
  - '[[SRD-Focus Energy|Focus Energy]]'
Number: 865
ShuffleToken: SRD-sirfetchd-ShuffleToken.png
Type1: Fighting
Type2: ''
Weight:
  Kilograms: 117.0
  Pounds: 257.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-sirfetchd-BookSprite.png|wsmall]]
> ![[SRD-sirfetchd-HomeSprite.png]]
> ![[SRD-sirfetchd-BoxSprite.png|htiny]]
> ![[SRD-sirfetchd-ShuffleToken.png|wsmall]]


*Wild Duck Pokemon*
*Only Farfetch’d that have survived many battles can go thought this evolution. They are very proud of their leek spear and leafen shield, When this Pokemon's leek withers, it will retire from combat.*

**DexID**:: 0865
**Name**:: Sirfetch'd
**Type**:: Fighting
**Abilities**:: [[SRD-Steadfast|Steadfast]] ([[SRD-Scrappy|Scrappy]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'6" / 0.8m
**Weight**: 257.9lbs / 117.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                            | Kind    | Special                           |
|:----------|:-----------------------------------|:--------|:----------------------------------|
| From      | [[SRD-Farfetch'd (Galarian Form)]] | Special | Score 3 Critical hits in 1 battle |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Sirfetch'd.md"
flatten moves as T
where file.path = this.file.path
```
