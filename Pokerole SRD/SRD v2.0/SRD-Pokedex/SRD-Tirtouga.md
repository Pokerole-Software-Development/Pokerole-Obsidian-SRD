---
Ability1: Solid Rock
Ability2: Sturdy
BookSprite: SRD-tirtouga-BookSprite.png
BoxSprite: SRD-tirtouga-BoxSprite.png
DexCategory: Prototurtle Pokemon
DexDescription: About 100 million years ago, these Pokemon swam in oceans. It is thought
  they also went on land to attack prey. One has been cloned from a fossil that was
  found a mile deep underwater.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Carracosta]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Swift Swim
HomeSprite: SRD-tirtouga-HomeSprite.png
Image: tirtouga.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Bide|Bide]]'
- - Starter
  - '[[SRD-Withdraw|Withdraw]]'
- - Starter
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Rollout|Rollout]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Protect|Protect]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Smack Down|Smack Down]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Ace
  - '[[SRD-Shell Smash|Shell Smash]]'
- - Ace
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Ace
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Body Slam|Body Slam]]'
Number: 564
ShuffleToken: SRD-tirtouga-ShuffleToken.png
Type1: Water
Type2: Rock
Weight:
  Kilograms: 16.5
  Pounds: 36.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-tirtouga-BookSprite.png|wsmall]]
> ![[SRD-tirtouga-HomeSprite.png]]
> ![[SRD-tirtouga-BoxSprite.png|htiny]]
> ![[SRD-tirtouga-ShuffleToken.png|wsmall]]


*Prototurtle Pokemon*
*About 100 million years ago, these Pokemon swam in oceans. It is thought they also went on land to attack prey. One has been cloned from a fossil that was found a mile deep underwater.*

**DexID**:: 0564
**Name**:: Tirtouga
**Type**:: Water / Rock
**Abilities**:: [[SRD-Solid Rock|Solid Rock]] / [[SRD-Sturdy|Sturdy]] ([[SRD-Swift Swim|Swift Swim]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'3" / 0.7m
**Weight**: 36.4lbs / 16.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon            | Kind   | Speed   |
|:----------|:-------------------|:-------|:--------|
| To        | [[SRD-Carracosta]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Tirtouga.md"
flatten moves as T
where file.path = this.file.path
```
