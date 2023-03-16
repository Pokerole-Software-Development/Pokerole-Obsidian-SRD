---
Ability1: Cheek Pouch
Ability2: ''
BookSprite: SRD-skwovet-BookSprite.png
BoxSprite: SRD-skwovet-BoxSprite.png
DexCategory: Cheeky Pokemon
DexDescription: They love to feed on berries and nuts they store on their cheeks,
  they can get very anxious if its cheeks are empty. If you feed one of them they
  will follow you and call for others so you feed them as well.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Greedent]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Gluttony
HomeSprite: SRD-skwovet-HomeSprite.png
Image: skwovet.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Stuff Cheeks|Stuff Cheeks]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Stockpile|Stockpile]]'
- - Amateur
  - '[[SRD-Swallow|Swallow]]'
- - Amateur
  - '[[SRD-Spit Up|Spit Up]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - Amateur
  - '[[SRD-Rest|Rest]]'
- - Amateur
  - '[[SRD-Counter|Counter]]'
- - Amateur
  - '[[SRD-Bullet Seed|Bullet Seed]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Super Fang|Super Fang]]'
- - Ace
  - '[[SRD-Belch|Belch]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Pro
  - '[[SRD-Rollout|Rollout]]'
- - Pro
  - '[[SRD-Crunch|Crunch]]'
Number: 819
ShuffleToken: SRD-skwovet-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 2.5
  Pounds: 5.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-skwovet-BookSprite.png|wsmall]]
> ![[SRD-skwovet-HomeSprite.png]]
> ![[SRD-skwovet-BoxSprite.png|htiny]]
> ![[SRD-skwovet-ShuffleToken.png|wsmall]]


*Cheeky Pokemon*
*They love to feed on berries and nuts they store on their cheeks, they can get very anxious if its cheeks are empty. If you feed one of them they will follow you and call for others so you feed them as well.*

**DexID**:: 0819
**Name**:: Skwovet
**Type**:: Normal
**Abilities**:: [[SRD-Cheek Pouch|Cheek Pouch]] ([[SRD-Gluttony|Gluttony]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 5.5lbs / 2.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Greedent]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Skwovet.md"
flatten moves as T
where file.path = this.file.path
```
