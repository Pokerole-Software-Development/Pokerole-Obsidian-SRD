---
Ability1: Strong Jaw
Ability2: ''
BookSprite: SRD-boltund-BookSprite.png
BoxSprite: SRD-boltund-BoxSprite.png
DexCategory: Dog Pokemon
DexDescription: It sends electricity through its legs to boost their speed, it easily
  breaks 50 mph. They get destructive and stressed if you do not take them out to
  run daily, otherwise they are chill and easygoing Pokemon.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Yamper]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Competitive
HomeSprite: SRD-boltund-HomeSprite.png
Image: boltund.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Electrify|Electrify]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Nuzzle|Nuzzle]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - Amateur
  - '[[SRD-Spark|Spark]]'
- - Amateur
  - '[[SRD-Charm|Charm]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Charge|Charge]]'
- - Ace
  - '[[SRD-Wild Charge|Wild Charge]]'
- - Ace
  - '[[SRD-Play Rough|Play Rough]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Electric Terrain|Electric Terrain]]'
- - Pro
  - '[[SRD-Psychic Fangs|Psychic Fangs]]'
- - Pro
  - '[[SRD-Dig|Dig]]'
- - Pro
  - '[[SRD-Thunder Fang|Thunder Fang]]'
Number: 836
ShuffleToken: SRD-boltund-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 34.0
  Pounds: 75.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-boltund-BookSprite.png|wsmall]]
> ![[SRD-boltund-HomeSprite.png]]
> ![[SRD-boltund-BoxSprite.png|htiny]]
> ![[SRD-boltund-ShuffleToken.png|wsmall]]


*Dog Pokemon*
*It sends electricity through its legs to boost their speed, it easily breaks 50 mph. They get destructive and stressed if you do not take them out to run daily, otherwise they are chill and easygoing Pokemon.*

**DexID**:: 0836
**Name**:: Boltund
**Type**:: Electric
**Abilities**:: [[SRD-Strong Jaw|Strong Jaw]] ([[SRD-Competitive|Competitive]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'3" / 1.0m
**Weight**: 75.0lbs / 34.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Yamper]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Boltund.md"
flatten moves as T
where file.path = this.file.path
```
