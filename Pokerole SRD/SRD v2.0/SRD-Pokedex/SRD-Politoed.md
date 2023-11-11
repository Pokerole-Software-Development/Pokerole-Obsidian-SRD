---
Ability1: Water Absorb
Ability2: Damp
BookSprite: SRD-politoed-BookSprite.png
BoxSprite: SRD-politoed-BoxSprite.png
DexCategory: Frog Pokemon
DexDescription: "It lives with Poliwags and Poliwhirls near ponds and lakes, but there\u2019\
  s rarely more than one. Politoed is the leader and acts as the king of the group.\
  \ It is an easy-going but proud Pokemon."
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: King's Rock
  Kind: Trade
  Pokemon: '[[SRD-Poliwhirl]]'
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Drizzle
HomeSprite: SRD-politoed-HomeSprite.png
Image: politoed.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bubble Beam|Bubble Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hypnosis|Hypnosis]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Double Slap|Double Slap]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Perish Song|Perish Song]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Swagger|Swagger]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bounce|Bounce]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hyper Voice|Hyper Voice]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mud Shot|Mud Shot]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Icy Wind|Icy Wind]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Refresh|Refresh]]'
Number: 186
ShuffleToken: SRD-politoed-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 33.9
  Pounds: 74.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-politoed-BookSprite.png|wsmall]]
> ![[SRD-politoed-HomeSprite.png]]
> ![[SRD-politoed-BoxSprite.png|htiny]]
> ![[SRD-politoed-ShuffleToken.png|wsmall]]


*Frog Pokemon*
*It lives with Poliwags and Poliwhirls near ponds and lakes, but there’s rarely more than one. Politoed is the leader and acts as the king of the group. It is an easy-going but proud Pokemon.*

**DexID**:: 0186
**Name**:: Politoed
**Type**:: Water
**Abilities**:: [[SRD-Water Absorb|Water Absorb]] / [[SRD-Damp|Damp]] ([[SRD-Drizzle|Drizzle]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 3'6" / 1.1m
**Weight**: 74.7lbs / 33.9kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Item        |
|:----------|:------------------|:-------|:------------|
| From      | [[SRD-Poliwhirl]] | Trade  | King's Rock |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Politoed.md"
flatten moves as T
where file.path = this.file.path
```
