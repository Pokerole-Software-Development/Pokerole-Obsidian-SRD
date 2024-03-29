---
Ability1: Immunity
Ability2: Thick Fat
BookSprite: SRD-snorlax-BookSprite.png
BoxSprite: SRD-snorlax-BoxSprite.png
DexCategory: Sleeping Pokemon
DexDescription: "Snorlax's typical day consists of eating and sleeping. It is such\
  \ a docile Pokemon that children use its big belly as a place to play. It only attacks\
  \ when it\u2019s awoken harshly. Fortunately it is a heavy sleeper."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Stat
  Pokemon: '[[SRD-Munchlax]]'
  Stat: Happiness
  Value: 4
GenderType: ''
Height:
  Feet: 6.9
  Meters: 2.1
HiddenAbility: Gluttony
HomeSprite: SRD-snorlax-HomeSprite.png
Image: snorlax.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Defense Curl|Defense Curl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Amnesia|Amnesia]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Lick|Lick]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Yawn|Yawn]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Chip Away|Chip Away]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Body Slam|Body Slam]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rest|Rest]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Snore|Snore]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sleep Talk|Sleep Talk]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rollout|Rollout]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Block|Block]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Crunch|Crunch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Belly Drum|Belly Drum]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Heavy Slam|Heavy Slam]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Giga Impact|Giga Impact]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-High Horsepower|High Horsepower]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Outrage|Outrage]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Gunk Shot|Gunk Shot]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Self Destruct|Self Destruct]]'
Number: 143
ShuffleToken: SRD-snorlax-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 460.0
  Pounds: 1014.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-snorlax-BookSprite.png|wsmall]]
> ![[SRD-snorlax-HomeSprite.png]]
> ![[SRD-snorlax-BoxSprite.png|htiny]]
> ![[SRD-snorlax-ShuffleToken.png|wsmall]]


*Sleeping Pokemon*
*Snorlax's typical day consists of eating and sleeping. It is such a docile Pokemon that children use its big belly as a place to play. It only attacks when it’s awoken harshly. Fortunately it is a heavy sleeper.*

**DexID**:: 0143
**Name**:: Snorlax
**Type**:: Normal
**Abilities**:: [[SRD-Immunity|Immunity]] / [[SRD-Thick Fat|Thick Fat]] ([[SRD-Gluttony|Gluttony]])
**Base HP**:: 8

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 6'9" / 2.1m
**Weight**: 1014.1lbs / 460.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Stat      |   Value |
|:----------|:-----------------|:-------|:----------|--------:|
| From      | [[SRD-Munchlax]] | Stat   | Happiness |       4 |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Snorlax.md"
flatten moves as T
where file.path = this.file.path
```
