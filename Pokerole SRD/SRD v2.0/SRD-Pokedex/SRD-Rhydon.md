---
Ability1: Lightning Rod
Ability2: Rock Head
BookSprite: SRD-rhydon-BookSprite.png
BoxSprite: SRD-rhydon-BoxSprite.png
DexCategory: Drill Pokemon
DexDescription: It has a horn that serves as a drill for destroying rocks and boulders.
  Rhydon occasionally goes for a swim in rivers and even magma pools. Its great resistance
  prevents it from taking any damage.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Rhyhorn]]'
  Speed: Slow
- Evolves: To
  Item: Protector
  Kind: Trade
  Pokemon: '[[SRD-Rhyperior]]'
GenderType: ''
Height:
  Feet: 6.2
  Meters: 1.9
HiddenAbility: Reckless
HomeSprite: SRD-rhydon-HomeSprite.png
Image: rhydon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Horn Attack|Horn Attack]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Stomp|Stomp]]'
- - Beginner
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Beginner
  - '[[SRD-Smack Down|Smack Down]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Amateur
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Amateur
  - '[[SRD-Chip Away|Chip Away]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Drill Run|Drill Run]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Ace
  - '[[SRD-Stone Edge|Stone Edge]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Horn Drill|Horn Drill]]'
- - Ace
  - '[[SRD-Megahorn|Megahorn]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dragon Rush|Dragon Rush]]'
- - Pro
  - '[[SRD-Skull Bash|Skull Bash]]'
- - Pro
  - '[[SRD-Smart Strike|Smart Strike]]'
Number: 112
ShuffleToken: SRD-rhydon-ShuffleToken.png
Type1: Ground
Type2: Rock
Weight:
  Kilograms: 120.0
  Pounds: 264.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-rhydon-BookSprite.png|wsmall]]
> ![[SRD-rhydon-HomeSprite.png]]
> ![[SRD-rhydon-BoxSprite.png|htiny]]
> ![[SRD-rhydon-ShuffleToken.png|wsmall]]


*Drill Pokemon*
*It has a horn that serves as a drill for destroying rocks and boulders. Rhydon occasionally goes for a swim in rivers and even magma pools. Its great resistance prevents it from taking any damage.*

**DexID**:: 0112
**Name**:: Rhydon
**Type**:: Ground / Rock
**Abilities**:: [[SRD-Lightning Rod|Lightning Rod]] / [[SRD-Rock Head|Rock Head]] ([[SRD-Reckless|Reckless]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 6'2" / 1.9m
**Weight**: 264.6lbs / 120.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   | Item      |
|:----------|:------------------|:-------|:--------|:----------|
| From      | [[SRD-Rhyhorn]]   | Level  | Slow    |           |
| To        | [[SRD-Rhyperior]] | Trade  |         | Protector |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Rhydon.md"
flatten moves as T
where file.path = this.file.path
```
