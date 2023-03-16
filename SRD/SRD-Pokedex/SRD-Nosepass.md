---
Ability1: Sturdy
Ability2: Magnet Pull
BookSprite: SRD-nosepass-BookSprite.png
BoxSprite: SRD-nosepass-BoxSprite.png
DexCategory: Nosepass Pokemon
DexDescription: Their magnetic noses always point to the north. They were thought
  to be immobile, but it was recently revealed that they actually move 3/8 of an inch
  every year. They get a little crazy when magnets are close.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Special
  Pokemon: '[[SRD-Probopass]]'
  Special: A trip to New Mauville
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Sand Force
HomeSprite: SRD-nosepass-HomeSprite.png
Image: nosepass.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Harden|Harden]]'
- - Beginner
  - '[[SRD-Block|Block]]'
- - Beginner
  - '[[SRD-Rock Throw|Rock Throw]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Amateur
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Amateur
  - '[[SRD-Rest|Rest]]'
- - Amateur
  - '[[SRD-Spark|Spark]]'
- - Amateur
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Amateur
  - '[[SRD-Power Gem|Power Gem]]'
- - Amateur
  - '[[SRD-Sandstorm|Sandstorm]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - Ace
  - '[[SRD-Earth Power|Earth Power]]'
- - Ace
  - '[[SRD-Stone Edge|Stone Edge]]'
- - Ace
  - '[[SRD-Lock-On|Lock-On]]'
- - Ace
  - '[[SRD-Zap Cannon|Zap Cannon]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Pro
  - '[[SRD-Self Destruct|Self Destruct]]'
- - Pro
  - '[[SRD-Magic Coat|Magic Coat]]'
Number: 299
ShuffleToken: SRD-nosepass-ShuffleToken.png
Type1: Rock
Type2: ''
Weight:
  Kilograms: 97.0
  Pounds: 213.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-nosepass-BookSprite.png|wsmall]]
> ![[SRD-nosepass-HomeSprite.png]]
> ![[SRD-nosepass-BoxSprite.png|htiny]]
> ![[SRD-nosepass-ShuffleToken.png|wsmall]]


*Nosepass Pokemon*
*Their magnetic noses always point to the north. They were thought to be immobile, but it was recently revealed that they actually move 3/8 of an inch every year. They get a little crazy when magnets are close.*

**DexID**:: 0299
**Name**:: Nosepass
**Type**:: Rock
**Abilities**:: [[SRD-Sturdy|Sturdy]] / [[SRD-Magnet Pull|Magnet Pull]] ([[SRD-Sand Force|Sand Force]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'3" / 1.0m
**Weight**: 213.8lbs / 97.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon           | Kind    | Special                |
|:----------|:------------------|:--------|:-----------------------|
| To        | [[SRD-Probopass]] | Special | A trip to New Mauville |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Nosepass.md"
flatten moves as T
where file.path = this.file.path
```
