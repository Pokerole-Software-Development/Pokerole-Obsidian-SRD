---
Ability1: Steadfast
Ability2: ''
BookSprite: SRD-farfetchd-galarian-form-BookSprite.png
BoxSprite: SRD-farfetchd-galarian-form-BoxSprite.png
DexCategory: Wild Duck Pokemon
DexDescription: The stalks of leeks are thicker and longer in the Galar region, this
  has allowed Farfetch'd fare better than their Kanto counterparts. It has also made
  them hardier and warrior-like. They are still delicious, though.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Special
  Pokemon: '[[SRD-Sirfetch''d]]'
  Special: Score 3 Critical hits in 1 battle
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Scrappy
HomeSprite: SRD-farfetchd-galarian-form-HomeSprite.png
Image: farfetchd-galarian-form.png
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
- - Beginner
  - '[[SRD-Rock Smash|Rock Smash]]'
- - '---------------------------'
  - '---------------------------'
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
  - '[[SRD-Leaf Blade|Leaf Blade]]'
- - Ace
  - '[[SRD-Final Gambit|Final Gambit]]'
- - Ace
  - '[[SRD-Brave Bird|Brave Bird]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Solar Beam|Solar Beam]]'
- - Pro
  - '[[SRD-Steel Wing|Steel Wing]]'
- - Pro
  - '[[SRD-Feather Dance|Feather Dance]]'
Number: 83
ShuffleToken: SRD-farfetchd-galarian-form-ShuffleToken.png
Type1: Fighting
Type2: ''
Weight:
  Kilograms: 42.0
  Pounds: 92.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-farfetchd-galarian-form-BookSprite.png|wsmall]]
> ![[SRD-farfetchd-galarian-form-HomeSprite.png]]
> ![[SRD-farfetchd-galarian-form-BoxSprite.png|htiny]]
> ![[SRD-farfetchd-galarian-form-ShuffleToken.png|wsmall]]


*Wild Duck Pokemon*
*The stalks of leeks are thicker and longer in the Galar region, this has allowed Farfetch'd fare better than their Kanto counterparts. It has also made them hardier and warrior-like. They are still delicious, though.*

**DexID**:: 0083G
**Name**:: Farfetch'd (Galarian Form)
**Type**:: Fighting
**Abilities**:: [[SRD-Steadfast|Steadfast]] ([[SRD-Scrappy|Scrappy]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'6" / 0.8m
**Weight**: 92.6lbs / 42.0kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon            | Kind    | Special                           |
|:----------|:-------------------|:--------|:----------------------------------|
| To        | [[SRD-Sirfetch'd]] | Special | Score 3 Critical hits in 1 battle |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Farfetch'd (Galarian Form).md"
flatten moves as T
where file.path = this.file.path
```
