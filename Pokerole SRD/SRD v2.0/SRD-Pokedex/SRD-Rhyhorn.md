---
Ability1: Lightning Rod
Ability2: Rock Head
BookSprite: SRD-rhyhorn-BookSprite.png
BoxSprite: SRD-rhyhorn-BoxSprite.png
DexCategory: Spikes Pokemon
DexDescription: It lives in grasslands and rough terrains. It is covered with a thick
  hide and it tramples any threats by running towards them. It is not very smart,
  though. It can keep trampling things for hours just because.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Rhydon]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Reckless
HomeSprite: SRD-rhyhorn-HomeSprite.png
Image: rhyhorn.png
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
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Pro
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Pro
  - '[[SRD-Fire Fang|Fire Fang]]'
Number: 111
ShuffleToken: SRD-rhyhorn-ShuffleToken.png
Type1: Ground
Type2: Rock
Weight:
  Kilograms: 115.0
  Pounds: 253.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-rhyhorn-BookSprite.png|wsmall]]
> ![[SRD-rhyhorn-HomeSprite.png]]
> ![[SRD-rhyhorn-BoxSprite.png|htiny]]
> ![[SRD-rhyhorn-ShuffleToken.png|wsmall]]


*Spikes Pokemon*
*It lives in grasslands and rough terrains. It is covered with a thick hide and it tramples any threats by running towards them. It is not very smart, though. It can keep trampling things for hours just because.*

**DexID**:: 0111
**Name**:: Rhyhorn
**Type**:: Ground / Rock
**Abilities**:: [[SRD-Lightning Rod|Lightning Rod]] / [[SRD-Rock Head|Rock Head]] ([[SRD-Reckless|Reckless]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 3'3" / 1.0m
**Weight**: 253.5lbs / 115.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| To        | [[SRD-Rhydon]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Rhyhorn.md"
flatten moves as T
where file.path = this.file.path
```
