---
Ability1: Swarm
Ability2: Frisk
BookSprite: SRD-orbeetle-BookSprite.png
BoxSprite: SRD-orbeetle-BoxSprite.png
DexCategory: Seven Spot Pokemon
DexDescription: "It\u2019s famous for its high intelligence and the large size of\
  \ its brain. It has immense psychic power. They patrol their territory as floating\
  \ sentries, focusing a ray of light over any  intruder, even if they are miles away."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Dottler]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Telepathy
HomeSprite: SRD-orbeetle-HomeSprite.png
Image: orbeetle.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Struggle Bug|Struggle Bug]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - Beginner
  - '[[SRD-Light Screen|Light Screen]]'
- - Beginner
  - '[[SRD-Reflect|Reflect]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Magic Coat|Magic Coat]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Amateur
  - '[[SRD-Ally Switch|Ally Switch]]'
- - Amateur
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - Amateur
  - '[[SRD-Mirror Coat|Mirror Coat]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-After You|After You]]'
- - Ace
  - '[[SRD-Calm Mind|Calm Mind]]'
- - Ace
  - '[[SRD-Psychic Terrain|Psychic Terrain]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Infestation|Infestation]]'
- - Pro
  - '[[SRD-Recover|Recover]]'
- - Pro
  - '[[SRD-Imprison|Imprison]]'
Number: 826
ShuffleToken: SRD-orbeetle-ShuffleToken.png
Type1: Bug
Type2: Psychic
Weight:
  Kilograms: 40.8
  Pounds: 89.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-orbeetle-BookSprite.png|wsmall]]
> ![[SRD-orbeetle-HomeSprite.png]]
> ![[SRD-orbeetle-BoxSprite.png|htiny]]
> ![[SRD-orbeetle-ShuffleToken.png|wsmall]]


*Seven Spot Pokemon*
*It’s famous for its high intelligence and the large size of its brain. It has immense psychic power. They patrol their territory as floating sentries, focusing a ray of light over any  intruder, even if they are miles away.*

**DexID**:: 0826
**Name**:: Orbeetle
**Type**:: Bug / Psychic
**Abilities**:: [[SRD-Swarm|Swarm]] / [[SRD-Frisk|Frisk]] ([[SRD-Telepathy|Telepathy]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::7)     |

**Height**: 1'3" / 0.4m
**Weight**: 89.9lbs / 40.8kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Dottler]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Orbeetle.md"
flatten moves as T
where file.path = this.file.path
```
