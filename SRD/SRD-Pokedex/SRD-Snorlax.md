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
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Defense Curl|Defense Curl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Amnesia|Amnesia]]'
- - Beginner
  - '[[SRD-Lick|Lick]]'
- - Beginner
  - '[[SRD-Yawn|Yawn]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Chip Away|Chip Away]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - Amateur
  - '[[SRD-Rest|Rest]]'
- - Amateur
  - '[[SRD-Snore|Snore]]'
- - Amateur
  - '[[SRD-Sleep Talk|Sleep Talk]]'
- - Amateur
  - '[[SRD-Rollout|Rollout]]'
- - Amateur
  - '[[SRD-Block|Block]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Belly Drum|Belly Drum]]'
- - Ace
  - '[[SRD-Heavy Slam|Heavy Slam]]'
- - Ace
  - '[[SRD-Giga Impact|Giga Impact]]'
- - Ace
  - '[[SRD-High Horsepower|High Horsepower]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
- - Pro
  - '[[SRD-Gunk Shot|Gunk Shot]]'
- - Pro
  - '[[SRD-Self Destruct|Self Destruct]]'
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
FROM "SRD/SRD-Pokedex/SRD-Snorlax.md"
flatten moves as T
where file.path = this.file.path
```
