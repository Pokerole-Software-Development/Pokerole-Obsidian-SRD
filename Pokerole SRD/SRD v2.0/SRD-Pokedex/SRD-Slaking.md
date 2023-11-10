---
Ability1: Truant
Ability2: ''
BookSprite: SRD-slaking-BookSprite.png
BoxSprite: SRD-slaking-BoxSprite.png
DexCategory: Lazy Pokemon
DexDescription: They spend all day sleeping and eating grass that grows within their
  reach. Sometimes they live beneath trees, waiting for fruits to fall. They dislike
  intruders on their territory but rarely do anything about them.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Vigoroth]]'
  Speed: Fast
GenderType: ''
Height:
  Feet: 6.6
  Meters: 2.0
HiddenAbility: ''
HomeSprite: SRD-slaking-HomeSprite.png
Image: slaking.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Yawn|Yawn]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Encore|Encore]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Punishment|Punishment]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Slack Off|Slack Off]]'
- - Amateur
  - '[[SRD-Covet|Covet]]'
- - Amateur
  - '[[SRD-Encore|Encore]]'
- - Amateur
  - '[[SRD-Fling|Fling]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Ace
  - '[[SRD-Chip Away|Chip Away]]'
- - Ace
  - '[[SRD-Counter|Counter]]'
- - Ace
  - '[[SRD-Flail|Flail]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Block|Block]]'
- - Pro
  - '[[SRD-Focus Punch|Focus Punch]]'
- - Pro
  - '[[SRD-Gunk Shot|Gunk Shot]]'
Number: 289
ShuffleToken: SRD-slaking-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 130.5
  Pounds: 287.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-slaking-BookSprite.png|wsmall]]
> ![[SRD-slaking-HomeSprite.png]]
> ![[SRD-slaking-BoxSprite.png|htiny]]
> ![[SRD-slaking-ShuffleToken.png|wsmall]]


*Lazy Pokemon*
*They spend all day sleeping and eating grass that grows within their reach. Sometimes they live beneath trees, waiting for fruits to fall. They dislike intruders on their territory but rarely do anything about them.*

**DexID**:: 0289
**Name**:: Slaking
**Type**:: Normal
**Abilities**:: [[SRD-Truant|Truant]]
**Base HP**:: 8

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::4)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 6'6" / 2.0m
**Weight**: 287.7lbs / 130.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Vigoroth]] | Level  | Fast    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Slaking.md"
flatten moves as T
where file.path = this.file.path
```
