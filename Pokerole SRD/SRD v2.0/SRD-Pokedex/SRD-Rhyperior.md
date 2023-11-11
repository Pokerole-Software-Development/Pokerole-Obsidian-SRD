---
Ability1: Lightning Rod
Ability2: Solid Rock
BookSprite: SRD-rhyperior-BookSprite.png
BoxSprite: SRD-rhyperior-BoxSprite.png
DexCategory: Drill Pokemon
DexDescription: They have rarely been seen in the wild and only in the tallest mountains.
  It has holes on its hands which are used like canons to shoot boulders. Be careful,
  they are very aggressive but not very smart.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Protector
  Kind: Trade
  Pokemon: '[[SRD-Rhydon]]'
GenderType: ''
Height:
  Feet: 7.9
  Meters: 2.4
HiddenAbility: Reckless
HomeSprite: SRD-rhyperior-HomeSprite.png
Image: rhyperior.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tail Whip|Tail Whip]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Horn Attack|Horn Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Stomp|Stomp]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Poison Jab|Poison Jab]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rock Blast|Rock Blast]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Chip Away|Chip Away]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Take Down|Take Down]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hammer Arm|Hammer Arm]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Drill Run|Drill Run]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Stone Edge|Stone Edge]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Horn Drill|Horn Drill]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Megahorn|Megahorn]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rock Wrecker|Rock Wrecker]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Guard Split|Guard Split]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Smart Strike|Smart Strike]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dragon Rush|Dragon Rush]]'
Number: 464
ShuffleToken: SRD-rhyperior-ShuffleToken.png
Type1: Ground
Type2: Rock
Weight:
  Kilograms: 282.8
  Pounds: 623.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-rhyperior-BookSprite.png|wsmall]]
> ![[SRD-rhyperior-HomeSprite.png]]
> ![[SRD-rhyperior-BoxSprite.png|htiny]]
> ![[SRD-rhyperior-ShuffleToken.png|wsmall]]


*Drill Pokemon*
*They have rarely been seen in the wild and only in the tallest mountains. It has holes on its hands which are used like canons to shoot boulders. Be careful, they are very aggressive but not very smart.*

**DexID**:: 0464
**Name**:: Rhyperior
**Type**:: Ground / Rock
**Abilities**:: [[SRD-Lightning Rod|Lightning Rod]] / [[SRD-Solid Rock|Solid Rock]] ([[SRD-Reckless|Reckless]])
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 7'9" / 2.4m
**Weight**: 623.5lbs / 282.8kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon        | Kind   | Item      |
|:----------|:---------------|:-------|:----------|
| From      | [[SRD-Rhydon]] | Trade  | Protector |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Rhyperior.md"
flatten moves as T
where file.path = this.file.path
```
