---
Ability1: Steadfast
Ability2: ''
BookSprite: SRD-gallade-BookSprite.png
BoxSprite: SRD-gallade-BoxSprite.png
DexCategory: Blade Pokemon
DexDescription: "This Pokemon is male only. He has an extreme sense of courtesy. In\
  \ a battle, it uses the blades on his arms as if they were swords. It is a loyal\
  \ Pokemon and won\u2019t doubt to fiercely protect its trainer."
EventAbilities: ''
Evolutions:
- Evolves: From
  Gender: Male
  Item: Dawn Stone
  Kind: Special
  Pokemon: '[[SRD-Kirlia]]'
- Evolves: To
  Item: Galladite
  Kind: Mega
  Pokemon: '[[SRD-Gallade (Mega Form)]]'
GenderType: M
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: Justified
HomeSprite: SRD-gallade-HomeSprite.png
Image: gallade.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Confusion|Confusion]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Double Team|Double Team]]'
- - Beginner
  - '[[SRD-Teleport|Teleport]]'
- - Beginner
  - '[[SRD-Quick Guard|Quick Guard]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-False Swipe|False Swipe]]'
- - Amateur
  - '[[SRD-Feint|Feint]]'
- - Amateur
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - Amateur
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - Amateur
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Amateur
  - '[[SRD-Psycho Cut|Psycho Cut]]'
- - Amateur
  - '[[SRD-Helping Hand|Helping Hand]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Leaf Blade|Leaf Blade]]'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[SRD-Protect|Protect]]'
- - Ace
  - '[[SRD-Close Combat|Close Combat]]'
- - Ace
  - '[[SRD-Stored Power|Stored Power]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
- - Pro
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
Number: 475
ShuffleToken: SRD-gallade-ShuffleToken.png
Type1: Psychic
Type2: Fighting
Weight:
  Kilograms: 52.0
  Pounds: 114.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-gallade-BookSprite.png|wsmall]]
> ![[SRD-gallade-HomeSprite.png]]
> ![[SRD-gallade-BoxSprite.png|htiny]]
> ![[SRD-gallade-ShuffleToken.png|wsmall]]


*Blade Pokemon*
*This Pokemon is male only. He has an extreme sense of courtesy. In a battle, it uses the blades on his arms as if they were swords. It is a loyal Pokemon and won’t doubt to fiercely protect its trainer.*

**DexID**:: 0475
**Name**:: Gallade
**Type**:: Psychic / Fighting
**Abilities**:: [[SRD-Steadfast|Steadfast]] ([[SRD-Justified|Justified]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 5'2" / 1.6m
**Weight**: 114.6lbs / 52.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon                     | Kind    | Item       | Gender   |
|:----------|:----------------------------|:--------|:-----------|:---------|
| From      | [[SRD-Kirlia]]              | Special | Dawn Stone | Male     |
| To        | [[SRD-Gallade (Mega Form)]] | Mega    | Galladite  |          |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Gallade.md"
flatten moves as T
where file.path = this.file.path
```
