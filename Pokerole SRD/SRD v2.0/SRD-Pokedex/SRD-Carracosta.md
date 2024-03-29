---
Ability1: Solid Rock
Ability2: Sturdy
BookSprite: SRD-carracosta-BookSprite.png
BoxSprite: SRD-carracosta-BoxSprite.png
DexCategory: Prototurtle Pokemon
DexDescription: They can live both in ocean and land. It can knock out a foe with
  a slap from one of its powerful front fins and chew it up whole. Fortunately, only
  one specimen on captivity remains.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Tirtouga]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Swift Swim
HomeSprite: SRD-carracosta-HomeSprite.png
Image: carracosta.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bide|Bide]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Withdraw|Withdraw]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rollout|Rollout]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bite|Bite]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Protect|Protect]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Aqua Jet|Aqua Jet]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Crunch|Crunch]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wide Guard|Wide Guard]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Brine|Brine]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Smack Down|Smack Down]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Curse|Curse]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Aqua Tail|Aqua Tail]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Shell Smash|Shell Smash]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rock Slide|Rock Slide]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rain Dance|Rain Dance]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Guard Split|Guard Split]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Iron Head|Iron Head]]'
Number: 565
ShuffleToken: SRD-carracosta-ShuffleToken.png
Type1: Water
Type2: Rock
Weight:
  Kilograms: 81.0
  Pounds: 178.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-carracosta-BookSprite.png|wsmall]]
> ![[SRD-carracosta-HomeSprite.png]]
> ![[SRD-carracosta-BoxSprite.png|htiny]]
> ![[SRD-carracosta-ShuffleToken.png|wsmall]]


*Prototurtle Pokemon*
*They can live both in ocean and land. It can knock out a foe with a slap from one of its powerful front fins and chew it up whole. Fortunately, only one specimen on captivity remains.*

**DexID**:: 0565
**Name**:: Carracosta
**Type**:: Water / Rock
**Abilities**:: [[SRD-Solid Rock|Solid Rock]] / [[SRD-Sturdy|Sturdy]] ([[SRD-Swift Swim|Swift Swim]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'9" / 1.2m
**Weight**: 178.6lbs / 81.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Tirtouga]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Carracosta.md"
flatten moves as T
where file.path = this.file.path
```
