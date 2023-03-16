---
Ability1: Rock Head
Ability2: Sturdy
BookSprite: SRD-golem-BookSprite.png
BoxSprite: SRD-golem-BoxSprite.png
DexCategory: Megaton Pokemon
DexDescription: It is rare to see in the wild since it lives high on the mountains.
  It withdraws its head and legs as if it were a turtle to roll around. There have
  been cases of Golem that resist dynamite blasts unscathed.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Trade
  Pokemon: '[[SRD-Graveler]]'
GenderType: ''
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: Sand Veil
HomeSprite: SRD-golem-HomeSprite.png
Image: golem.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Defense Curl|Defense Curl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Mud Sport|Mud Sport]]'
- - Beginner
  - '[[SRD-Rock Polish|Rock Polish]]'
- - Beginner
  - '[[SRD-Steamroller|Steamroller]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Magnitude|Magnitude]]'
- - Amateur
  - '[[SRD-Rock Throw|Rock Throw]]'
- - Amateur
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Amateur
  - '[[SRD-Smack Down|Smack Down]]'
- - Amateur
  - '[[SRD-Self Destruct|Self Destruct]]'
- - Amateur
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Amateur
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Explosion|Explosion]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Stone Edge|Stone Edge]]'
- - Ace
  - '[[SRD-Heavy Slam|Heavy Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Superpower|Superpower]]'
- - Pro
  - '[[SRD-Thunder Punch|Thunder Punch]]'
Number: 76
ShuffleToken: SRD-golem-ShuffleToken.png
Type1: Rock
Type2: Ground
Weight:
  Kilograms: 300.0
  Pounds: 661.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-golem-BookSprite.png|wsmall]]
> ![[SRD-golem-HomeSprite.png]]
> ![[SRD-golem-BoxSprite.png|htiny]]
> ![[SRD-golem-ShuffleToken.png|wsmall]]


*Megaton Pokemon*
*It is rare to see in the wild since it lives high on the mountains. It withdraws its head and legs as if it were a turtle to roll around. There have been cases of Golem that resist dynamite blasts unscathed.*

**DexID**:: 0076
**Name**:: Golem
**Type**:: Rock / Ground
**Abilities**:: [[SRD-Rock Head|Rock Head]] / [[SRD-Sturdy|Sturdy]] ([[SRD-Sand Veil|Sand Veil]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 4'6" / 1.4m
**Weight**: 661.4lbs / 300.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon          | Kind   |
|:----------|:-----------------|:-------|
| From      | [[SRD-Graveler]] | Trade  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Golem.md"
flatten moves as T
where file.path = this.file.path
```
