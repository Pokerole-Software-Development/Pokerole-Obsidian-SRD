---
Ability1: Sturdy
Ability2: Rock Head
BookSprite: SRD-sudowoodo-BookSprite.png
BoxSprite: SRD-sudowoodo-BoxSprite.png
DexCategory: Imitation Pokemon
DexDescription: "Sudowoodo camouflages itself as a tree to avoid being attacked by\
  \ enemies. However, because its arms remain green throughout the year, this Pokemon\
  \ is easy to identify in winter. It\u2019s a little wary of humans."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Move: Mimic
  Pokemon: '[[SRD-Bonsly]]'
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Rattled
HomeSprite: SRD-sudowoodo-HomeSprite.png
Image: sudowoodo.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Flail|Flail]]'
- - Starter
  - '[[SRD-Rock Throw|Rock Throw]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Low Kick|Low Kick]]'
- - Beginner
  - '[[SRD-Mimic|Mimic]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Wood Hammer|Wood Hammer]]'
- - Amateur
  - '[[SRD-Copycat|Copycat]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Rock Tomb|Rock Tomb]]'
- - Amateur
  - '[[SRD-Tearful Look|Tearful Look]]'
- - Amateur
  - '[[SRD-Block|Block]]'
- - Amateur
  - '[[SRD-Counter|Counter]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Stone Edge|Stone Edge]]'
- - Ace
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Ace
  - '[[SRD-Head Smash|Head Smash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fire Punch|Fire Punch]]'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Pro
  - '[[SRD-Self Destruct|Self Destruct]]'
Number: 185
ShuffleToken: SRD-sudowoodo-ShuffleToken.png
Type1: Rock
Type2: ''
Weight:
  Kilograms: 38.0
  Pounds: 83.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-sudowoodo-BookSprite.png|wsmall]]
> ![[SRD-sudowoodo-HomeSprite.png]]
> ![[SRD-sudowoodo-BoxSprite.png|htiny]]
> ![[SRD-sudowoodo-ShuffleToken.png|wsmall]]


*Imitation Pokemon*
*Sudowoodo camouflages itself as a tree to avoid being attacked by enemies. However, because its arms remain green throughout the year, this Pokemon is easy to identify in winter. It’s a little wary of humans.*

**DexID**:: 0185
**Name**:: Sudowoodo
**Type**:: Rock
**Abilities**:: [[SRD-Sturdy|Sturdy]] / [[SRD-Rock Head|Rock Head]] ([[SRD-Rattled|Rattled]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'9" / 1.2m
**Weight**: 83.8lbs / 38.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Move   |
|:----------|:---------------|:-------|:-------|
| From      | [[SRD-Bonsly]] | Level  | Mimic  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Sudowoodo.md"
flatten moves as T
where file.path = this.file.path
```
