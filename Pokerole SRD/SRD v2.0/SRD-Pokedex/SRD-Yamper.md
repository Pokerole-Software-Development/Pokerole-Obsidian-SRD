---
Ability1: Ball Fetch
Ability2: ''
BookSprite: SRD-yamper-BookSprite.png
BoxSprite: SRD-yamper-BoxSprite.png
DexCategory: Puppy Pokemon
DexDescription: Its energy and big smile make this Pokemon very popular as a herding
  dog. When it runs, it generates electricity from the base of its tail. It loves
  to fetch balls and if you give it some treats it will love you forever.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Boltund]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Rattled
HomeSprite: SRD-yamper-HomeSprite.png
Image: yamper.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Nuzzle|Nuzzle]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Roar|Roar]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Spark|Spark]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Charm|Charm]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Crunch|Crunch]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Charge|Charge]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wild Charge|Wild Charge]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Play Rough|Play Rough]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sand Attack|Sand Attack]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Flame Charge|Flame Charge]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Howl|Howl]]'
Number: 835
ShuffleToken: SRD-yamper-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 13.5
  Pounds: 29.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-yamper-BookSprite.png|wsmall]]
> ![[SRD-yamper-HomeSprite.png]]
> ![[SRD-yamper-BoxSprite.png|htiny]]
> ![[SRD-yamper-ShuffleToken.png|wsmall]]


*Puppy Pokemon*
*Its energy and big smile make this Pokemon very popular as a herding dog. When it runs, it generates electricity from the base of its tail. It loves to fetch balls and if you give it some treats it will love you forever.*

**DexID**:: 0835
**Name**:: Yamper
**Type**:: Electric
**Abilities**:: [[SRD-Ball Fetch|Ball Fetch]] ([[SRD-Rattled|Rattled]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'0" / 0.3m
**Weight**: 29.8lbs / 13.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Boltund]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Yamper.md"
flatten moves as T
where file.path = this.file.path
```
