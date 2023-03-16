---
Ability1: Cheek Pouch
Ability2: ''
BookSprite: SRD-greedent-BookSprite.png
BoxSprite: SRD-greedent-BoxSprite.png
DexCategory: Greedy Pokemon
DexDescription: They are a little dim-witted as they think on nothing but eating.
  Greedent hide and store berries on their tails, many of them fall of, becoming new
  trees the next year. Their teeth are very strong.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Skwovet]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Gluttony
HomeSprite: SRD-greedent-HomeSprite.png
Image: greedent.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Covet|Covet]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Stuff Cheeks|Stuff Cheeks]]'
- - Amateur
  - '[[SRD-Stockpile|Stockpile]]'
- - Amateur
  - '[[SRD-Swallow|Swallow]]'
- - Amateur
  - '[[SRD-Spit Up|Spit Up]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Rest|Rest]]'
- - Ace
  - '[[SRD-Counter|Counter]]'
- - Ace
  - '[[SRD-Bullet Seed|Bullet Seed]]'
- - Ace
  - '[[SRD-Super Fang|Super Fang]]'
- - Ace
  - '[[SRD-Belch|Belch]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Last Resort|Last Resort]]'
- - Pro
  - '[[SRD-Belly Drum|Belly Drum]]'
- - Pro
  - '[[SRD-Crunch|Crunch]]'
Number: 820
ShuffleToken: SRD-greedent-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 6.0
  Pounds: 13.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-greedent-BookSprite.png|wsmall]]
> ![[SRD-greedent-HomeSprite.png]]
> ![[SRD-greedent-BoxSprite.png|htiny]]
> ![[SRD-greedent-ShuffleToken.png|wsmall]]


*Greedy Pokemon*
*They are a little dim-witted as they think on nothing but eating. Greedent hide and store berries on their tails, many of them fall of, becoming new trees the next year. Their teeth are very strong.*

**DexID**:: 0820
**Name**:: Greedent
**Type**:: Normal
**Abilities**:: [[SRD-Cheek Pouch|Cheek Pouch]] ([[SRD-Gluttony|Gluttony]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'0" / 0.6m
**Weight**: 13.2lbs / 6.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Skwovet]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Greedent.md"
flatten moves as T
where file.path = this.file.path
```
