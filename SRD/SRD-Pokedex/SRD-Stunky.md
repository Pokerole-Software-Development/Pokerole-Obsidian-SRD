---
Ability1: Stench
Ability2: Aftermath
BookSprite: SRD-stunky-BookSprite.png
BoxSprite: SRD-stunky-BoxSprite.png
DexCategory: Skunk Pokemon
DexDescription: Over the years they have moved closer to towns and other human settlements.
  They release a foul liquid from their rear that stinks for days to scare away predators.
  But sometimes they do it just for fun.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Skuntank]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Keen Eye
HomeSprite: SRD-stunky-HomeSprite.png
Image: stunky.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Focus Energy|Focus Energy]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Poison Gas|Poison Gas]]'
- - Beginner
  - '[[SRD-Screech|Screech]]'
- - Beginner
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Smokescreen|Smokescreen]]'
- - Amateur
  - '[[SRD-Feint|Feint]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Toxic|Toxic]]'
- - Amateur
  - '[[SRD-Acid Spray|Acid Spray]]'
- - Amateur
  - '[[SRD-Venom Drench|Venom Drench]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[SRD-Memento|Memento]]'
- - Ace
  - '[[SRD-Belch|Belch]]'
- - Ace
  - '[[SRD-Explosion|Explosion]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Play Rough|Play Rough]]'
- - Pro
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Pro
  - '[[SRD-Flame Burst|Flame Burst]]'
Number: 434
ShuffleToken: SRD-stunky-ShuffleToken.png
Type1: Poison
Type2: Dark
Weight:
  Kilograms: 19.2
  Pounds: 42.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-stunky-BookSprite.png|wsmall]]
> ![[SRD-stunky-HomeSprite.png]]
> ![[SRD-stunky-BoxSprite.png|htiny]]
> ![[SRD-stunky-ShuffleToken.png|wsmall]]


*Skunk Pokemon*
*Over the years they have moved closer to towns and other human settlements. They release a foul liquid from their rear that stinks for days to scare away predators. But sometimes they do it just for fun.*

**DexID**:: 0434
**Name**:: Stunky
**Type**:: Poison / Dark
**Abilities**:: [[SRD-Stench|Stench]] / [[SRD-Aftermath|Aftermath]] ([[SRD-Keen Eye|Keen Eye]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'3" / 0.4m
**Weight**: 42.3lbs / 19.2kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Skuntank]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Stunky.md"
flatten moves as T
where file.path = this.file.path
```
