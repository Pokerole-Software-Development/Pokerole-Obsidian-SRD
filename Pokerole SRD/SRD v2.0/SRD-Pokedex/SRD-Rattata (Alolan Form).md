---
Ability1: Gluttony
Ability2: Hustle
BookSprite: SRD-rattata-alolan-form-BookSprite.png
BoxSprite: SRD-rattata-alolan-form-BoxSprite.png
DexCategory: Mouse Pokemon
DexDescription: "Rattata first came to Alola through cargo ships, it thrived and almost\
  \ destroyed the region\u2019s ecosystem. Attempts to exterminate this Pokemon made\
  \ it more vicious than its regular counterpart."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Raticate (Alolan Form)]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Thick Fat
HomeSprite: SRD-rattata-alolan-form-HomeSprite.png
Image: rattata-alolan-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hyper Fang|Hyper Fang]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sucker Punch|Sucker Punch]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Assurance|Assurance]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Crunch|Crunch]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Super Fang|Super Fang]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Endeavor|Endeavor]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Reversal|Reversal]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Snatch|Snatch]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Switcheroo|Switcheroo]]'
Number: 19
ShuffleToken: SRD-rattata-alolan-form-ShuffleToken.png
Type1: Dark
Type2: Normal
Weight:
  Kilograms: 3.8
  Pounds: 8.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-rattata-alolan-form-BookSprite.png|wsmall]]
> ![[SRD-rattata-alolan-form-HomeSprite.png]]
> ![[SRD-rattata-alolan-form-BoxSprite.png|htiny]]
> ![[SRD-rattata-alolan-form-ShuffleToken.png|wsmall]]


*Mouse Pokemon*
*Rattata first came to Alola through cargo ships, it thrived and almost destroyed the region’s ecosystem. Attempts to exterminate this Pokemon made it more vicious than its regular counterpart.*

**DexID**:: 0019A
**Name**:: Rattata (Alolan Form)
**Type**:: Dark / Normal
**Abilities**:: [[SRD-Gluttony|Gluttony]] / [[SRD-Hustle|Hustle]] ([[SRD-Thick Fat|Thick Fat]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 8.4lbs / 3.8kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon                        | Kind   | Speed   |
|:----------|:-------------------------------|:-------|:--------|
| To        | [[SRD-Raticate (Alolan Form)]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Rattata (Alolan Form).md"
flatten moves as T
where file.path = this.file.path
```
