---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-mismagius-BookSprite.png
BoxSprite: SRD-mismagius-BoxSprite.png
DexCategory: Magical Pokemon
DexDescription: Extremely rare. Their cries sound like incantations, hearing them
  gives you bad headaches and hallucinations. It is said that some Mismagius are benevolent
  and have granted good fortune to people they like.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Dusk Stone
  Kind: Stone
  Pokemon: '[[SRD-Misdreavus]]'
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: ''
HomeSprite: SRD-mismagius-HomeSprite.png
Image: mismagius.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Magical Leaf|Magical Leaf]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Lucky Chant|Lucky Chant]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Astonish|Astonish]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Power Gem|Power Gem]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psywave|Psywave]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Spite|Spite]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Phantom Force|Phantom Force]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mystical Fire|Mystical Fire]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wonder Room|Wonder Room]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Foul Play|Foul Play]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Nasty Plot|Nasty Plot]]'
Number: 429
ShuffleToken: SRD-mismagius-ShuffleToken.png
Type1: Ghost
Type2: ''
Weight:
  Kilograms: 4.4
  Pounds: 9.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-mismagius-BookSprite.png|wsmall]]
> ![[SRD-mismagius-HomeSprite.png]]
> ![[SRD-mismagius-BoxSprite.png|htiny]]
> ![[SRD-mismagius-ShuffleToken.png|wsmall]]


*Magical Pokemon*
*Extremely rare. Their cries sound like incantations, hearing them gives you bad headaches and hallucinations. It is said that some Mismagius are benevolent and have granted good fortune to people they like.*

**DexID**:: 0429
**Name**:: Mismagius
**Type**:: Ghost
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 3'0" / 0.9m
**Weight**: 9.7lbs / 4.4kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon            | Kind   | Item       |
|:----------|:-------------------|:-------|:-----------|
| From      | [[SRD-Misdreavus]] | Stone  | Dusk Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Mismagius.md"
flatten moves as T
where file.path = this.file.path
```
