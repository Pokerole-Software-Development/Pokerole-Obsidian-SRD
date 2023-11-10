---
Ability1: Gluttony
Ability2: Hustle
BookSprite: SRD-raticate-alolan-form-BookSprite.png
BoxSprite: SRD-raticate-alolan-form-BoxSprite.png
DexCategory: Mouse Pokemon
DexDescription: Alolan Raticate command their Rattata underlings to bring them food
  every night. Five star restaurants often struggle with these aggressive Pokemon
  nesting close to their grounds.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Rattata (Alolan Form)]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Thick Fat
HomeSprite: SRD-raticate-alolan-form-HomeSprite.png
Image: raticate-alolan-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Amateur
  - '[[SRD-Hyper Fang|Hyper Fang]]'
- - Amateur
  - '[[SRD-Assurance|Assurance]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Super Fang|Super Fang]]'
- - Ace
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Ace
  - '[[SRD-Endeavor|Endeavor]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Stockpile|Stockpile]]'
- - Pro
  - '[[SRD-Swallow|Swallow]]'
- - Pro
  - '[[SRD-Me First|Me First]]'
Number: 20
ShuffleToken: SRD-raticate-alolan-form-ShuffleToken.png
Type1: Dark
Type2: Normal
Weight:
  Kilograms: 25.5
  Pounds: 56.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-raticate-alolan-form-BookSprite.png|wsmall]]
> ![[SRD-raticate-alolan-form-HomeSprite.png]]
> ![[SRD-raticate-alolan-form-BoxSprite.png|htiny]]
> ![[SRD-raticate-alolan-form-ShuffleToken.png|wsmall]]


*Mouse Pokemon*
*Alolan Raticate command their Rattata underlings to bring them food every night. Five star restaurants often struggle with these aggressive Pokemon nesting close to their grounds.*

**DexID**:: 0020A
**Name**:: Raticate (Alolan Form)
**Type**:: Dark / Normal
**Abilities**:: [[SRD-Gluttony|Gluttony]] / [[SRD-Hustle|Hustle]] ([[SRD-Thick Fat|Thick Fat]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'3" / 0.7m
**Weight**: 56.2lbs / 25.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                       | Kind   | Speed   |
|:----------|:------------------------------|:-------|:--------|
| From      | [[SRD-Rattata (Alolan Form)]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Raticate (Alolan Form).md"
flatten moves as T
where file.path = this.file.path
```
